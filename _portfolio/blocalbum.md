---
layout: post
title: BlocFlix
thumbnail-path: "img/music.PNG"
short-description: BlocFlix is a Netflix replica for finding the best movies and watching them online.

---

{:.center}
![]({{ site.baseurl }}/img/music.PNG)

## Explanation

This music player is designed to allow user to play music online.  This project has three important pages, such as landing page, collection page, and album page.


## Problem

The project is required to create three pages using three important techniques in programming languages.  First, for landing page, user can choose, stream, and listen to music on desktop and mobile phone.

Second, on the collection page, users can view and choose one of millions of albums on the website.

Third, the album page lists all the music in a specific album. User can play and pause music in the main menu. In addition, there is a player bar which allows users to play, pause, forward, backward, adjust the progress bar and volume. 
 

## Solution

First, I was required to write the code from scratch using JavaScript Plain Language with HTML and CSS. 

Second, I need to refine the project using a library called JQuery. Last, we use the most powerful and structural framework called Angular JS to re-design the programs in professional and structural way.
    
## Results

It is the best fron-end project project. By request, I can send you my code or you can see my code in GitHub account.

## Conclusion

It is the best experience for me. Since this project allows me to create online music player in three different techniques. I have learned that each technique has its own benefit. Using plain JavaScript language from scratch without any help from library or framework is good for me as I can see the whole process and methods. 

Also, the loading speed of each page is fast. However, writing this program in JQuery is required less coding as we can call built-in methods in JQuery library, But it is quite slower in loading the pages.Each time of loading pages, the program need to contact JQuery library. 

Angular JS is more structural than any the two techniques. It reduces a lot of lines of codes, run fast as everyting is processed in the client site and reduce the continuous interaction with clients and server sides.

## Source Code's Snippet: 


{% highlight javascript %}
<!DOCTYPE html>
<html ng-app="blocJams">
<head lang="en">
    <meta charset="UTF-8">
    <title>Bloc Jams Angular</title>
     <meta name="viewport" content="width=device-width, initial-scale=1">
      <link rel="stylesheet" type="text/css" href="http://fonts.googleapis.com/css?family=Open+Sans:400,800,600,700,300">
     <link rel="stylesheet" type="text/css" href="http://code.ionicframework.com/ionicons/2.0.1/css/ionicons.min.css">
     <link rel="stylesheet" type="text/css" href="/styles/normalize.css">
     <link rel="stylesheet" type="text/css" href="/styles/main.css">
     <link rel="stylesheet" type="text/css" href="/styles/landing.css">
     <link rel="stylesheet" type="text/css" href="/styles/collection.css">
     <link rel="stylesheet" type="text/css" href="/styles/album.css">
     <link rel="stylesheet" type="text/css" href="/styles/player_bar.css">
     
</head>
<body>
   <nav class="navbar">
            <a href="index.html" class="logo">
                <img src="/assets/images/bloc_jams_logo.png" alt="bloc jams logo">
            </a>
            <div class="links-container">
                <a href="/templates/collection.html" class="navbar-link">Collection</a>
                
            </div>
        </nav>
        
        <ui-view></ui-view>
        
	<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.5.7/angular.min.js"></script>   
   <script src="https://cdnjs.cloudflare.com/ajax/libs/angular-ui-router/0.2.15/angular-ui-router.min.js"></script>
   <script src="/scripts/controllers/LandingCtrl.js"></script>
   <script src="/scripts/app.js"></script>
   <script src="/scripts/Fixtures.js"></script>
   <script src="/scripts/controllers/CollectionCtrl.js"></script>
   <script src="/scripts/controllers/AlbumCtrl.js"></script>
   
</body>
</html>
{% endhighlight %}

  
