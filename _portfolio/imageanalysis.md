---
layout: post
title: Cellular Network Camera For Biology Research (Image Analysis)
thumbnail-path: "img/image_analysis.png"
short-description: Build a real time image analysis application on the cloud.

---

{:.center}
![]({{ site.baseurl }}/img/image_analysis_2.png)

## Objective
This project is created by team of  four students. I am playing a role as a software manager.
A real time image analysis application. 
- Capture and store images from camera (located on ground or on quadcopter) using microprocessor.
- Establish connection from microprocessor to Microsoft Azure via cell phone network.
- Upload images from microprocessor and store inside Microsoft Azure Server.
- Perform image analysis on Microsoft Azure.

## Solution

#### Strategy for Selection Components
- Use commercially available components to save on costs
- Build system around GoPro camera, commercial transmitter, and reciever
- Required to use software such as Microsoft Azure, and Internet of Things

#### Hardware Development
- Gopro Hero 4
- Transmitter
- Reciever
- Video Interception Device
- High Powered USB Hub
- Rasberry PI Model 2B
- Voltage Regulator

#### Software Development
- Scrum: an agile wat to manage a project
- Sprint: a set of period of completing work

Product Backlog:
- Take Pictures with video interception device
- Upload to Azure
- Use OpenCV with Visual Studio
- Process images with OpenCV
- Upload applications to Microsoft Azure (Cloud Computing)

Sprint (2 weeks period to develop the software)
- Microsoft Azure Storage
- Windows Internet of Things (Windows IoT)
- OpenCV with external libraries
- Image Analysis Algorithms (Histogram Oriented Gradient & Convex Hull Algorithm)
- Slowest Algorithm: Speed Up Robust Feature (SURF) Algorithm (Test Purposes)

## Results (Image Analysis)

#### HOG (Histogram Oriented Gradient)
- Overal Accuracy: 70%
- Processing Speed (Average): 5-10 seconds per per 64KB picture

#### CH (Convex Hull)
- Overall Accuracy: 75%
- Processing Speed (Average): 2 seconds per 64 KB picture

## Conclusion
- Able to capture images from GoPro using Rasberry PI 2B
- Real-time data transfer from Rasberry Pi to Microsoft Azure Storage
- Rudimentary Image Analysis
- Additional Accomplishment: Create a UI (User Interface), Full-automated the whole process, and created a image training technques.

## References
- Dr. Arnold S. Berger- Engineering Chair
- Dr. Pierre D. Mourad- Industrial Sponsor
- Dr. Wayne D. Kimura- Faculty Advisor
- Mr. Prasantha Jayakody- Microsoft Contact
- Mr. Jetoni Orcejola- Mechanical Engineering Student
- John Lynch- Mechanical Engineering Student
