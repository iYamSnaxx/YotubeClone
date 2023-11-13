# YotubeClone
YoutubeClone HTML/CSS
HTML: 


<!DOCTYPE html>
<html>
  <head>
    <title>Youtube.com Clone</title>
    <link rel="stylesheet" href="css-stylesheets/general.css">
    <link rel="stylesheet" href="css-stylesheets/header.css">
    <link rel="stylesheet" href="css-stylesheets/video.css">
   
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
  </head>
  <body>
    <div class="header">
      <div class="left-section">
          <img class="hamburger-menu" src="icons/hamburger-menu.svg">
          <img class="youtube-logo" src="icons/youtube-logo.svg">
      </div>
      <div class="middle-section">
        <input class="search-bar" type="text" placeholder="Search">
        <button class="search-button">
          <img class="search-icon" src="icons/search.svg">
        </button>
        <button class="voice-search-icon-button">
          <img class="voice-icon" src="icons/voice-search-icon.svg">
        </button>
      </div>
      <div class="right-section">
          right section
      </div>
      
     

    </div>
    
   
 <div class="video-grid"> 
    <div class="video-preview">
      <div class="thumbnail-row">
        <img class="thumbnail" src="photos/thumbnail-1.webp">
      </div>
    
   <div class="video-info-grid">
    <div class="channel-picture">
      <img class="profile-picture" src="channel-photos/channel-1.jpeg">
    </div>
    <div class="video-info">
      <p class="video-title">
        Talking Tech and AI with Google CEO Sundar Pichai!
      </p>
      <p class="creator">
        Marques Brownlee
      </p>
      <p class="views">
        3.4M views &#183 6 months ago
      </p>
    </div>
   </div>
 </div>

    
    <div class="video-preview">
      <div class="thumbnail-row">
        <img class="thumbnail" src="photos/thumbnail-2.webp">
      </div>

    <div class="video-info-grid">
    <div class="channel-picture">
      <img class="profile-picture" src="channel-photos/channel-2.jpeg">
    </div>
    <div class="video-info">
      <p class="video-title">
        Try not to laugh Challenge #9
      </p>
      <p class="creator">
        Markiplier
      </p>
      <p class="views">
        19M views &#183 4 years ago
      </p>
    </div>
    </div>
    </div>

    <div class="video-preview">
      <div class="thumbnail-row">
        <img class="thumbnail" src="photos/thumbnail-3.webp">
      </div>

    <div class="video-info-grid">
    <div class="channel-picture">
      <img class="profile-picture" src="channel-photos/channel-3.jpeg">
    </div>
    <div class="video-info">
      <p class="video-title">
        Crazy Tik Toks Taken Moments Before Disaster
      </p>
      <p class="creator">
        SSSniperWolf
      </p>
      <p class="views">
        12M views &#183 1 year ago
      </p>
    </div>
    </div>
    </div>

    <div class="video-preview">
      <div class="thumbnail-row">
        <img class="thumbnail" src="photos/thumbnail-4.webp">
      </div>

    <div class="video-info-grid">
    <div class="channel-picture">
      <img class="profile-picture" src="channel-photos/channel-4.jpeg">
    </div>
    <div class="video-info">
      <p class="video-title">
        The Simplest Math Problem No One Can Solve - Collatz Conjecture
      </p>
      <p class="creator">
        Veritasium
      </p>
      <p class="views">
        18M views &#183 4 months ago
      </p>
    </div>
    </div>
    </div>

    <div class="video-preview">
      <div class="thumbnail-row">
        <img class="thumbnail" src="photos/thumbnail-5.webp">
      </div>

    <div class="video-info-grid">
    <div class="channel-picture">
      <img class="profile-picture" src="channel-photos/channel-5.jpeg">
    </div>
    <div class="video-info">
      <p class="video-title">
        Kadane's Algorithm to Maximum Sum Subarray Problem
      </p>
      <p class="creator">
        CS Dojo
      </p>
      <p class="views">
        519K views &#183 5 years ago
      </p>
    </div>
    </div>
    </div>

    <div class="video-preview">
      <div class="thumbnail-row">
        <img class="thumbnail" src="photos/thumbnail-6.webp">
      </div>
      <div class="video-info-grid">
        <div class="channel-picture">
          <img class="profile-picture" src="channel-photos/channel-6.jpeg">
        </div>
        <div class="video-info">
          <p class="video-title">
            Anything You Can Fit In The Circle I'll Pay For
          </p>
          <p class="video-author">
            MrBeast
          </p>
          <p class="video-stats">
            141M views &#183; 1 year ago
          </p>
        </div>
      </div>
    </div>
    </div>
    
  </body>

</html>





CSS : 

General CSS - 

p{
  font-family: Roboto, Arial;
  margin-top: 0;
  margin-bottom: 0;
}

body{
  margin: 0;
}

Header CSS - 
.header{
  height: 55px;


  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.left-section{
  display: flex;
  align-items: center;
}
.hamburger-menu{
  height: 25px;
  margin-left: 24px;
  margin-right: 20px;
}

.youtube-logo{
  height: 20px;
}

.middle-section{
  flex: 1;
  margin-left: 70px;
  margin-right: 30px;
  max-width: 500px;
  display: flex;
  align-items: center;
}

.search-bar{
  flex: 1;
  height: 34px;
  padding-left: 10px;
  font-size: 16px;
  border-width: 1px;
  border-style: solid;
  border-color: rgb(192,192,192);
  border-radius: 2px;
  box-shadow: inset 1px 2px 3px rgba(0,0,0,0.05);
}

.search-bar::placeholder{
  font-family: roboto, Arial;
  font-size: 16px;
}

.search-button{
  height: 40px;
  width: 66px;
  background-color: rgb(240,240,240);
  border-width: 1px;
  border-style: solid;
  border-color: rgb(192,192,192);
  margin-left: -1px;
  margin-right: 8px;
}

.voice-search-icon-button{
  height: 40px;
  width: 60px;
}

.search-icon{
  height: 25px;
  margin-top: 4px;
}
.voice-icon{}
.right-section{
  background-color: lightblue;
  width: 200px;
  
}

.thumbnail{
  width: 100%;
}


.video-title{
  margin-top: 0;
  font-size: 14px;
  font-weight: 500;
  line-height: 20px;
  margin-bottom: 12px;
}

.video-info-grid {
  display: grid;
  grid-template-columns: 50px 1fr;
}

.profile-picture{
  width: 40px;
  border-radius: 50px;
}

.thumbnail-row{
  margin-bottom: 12px;
}

.creator, .views{
  font-size: 12px;
  color:rgb(96,96, 96);
}

.creator{
  margin-bottom: 4px;
}




.video-grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  column-gap: 16px;
  row-gap: 40px;
}
