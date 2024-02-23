
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <meta name="author" content="Jayapriya">
    <meta name="description " content="describe an image">
    <link rel="stylesheet" href="assets/css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>PROJECT DASHBOARD</title>
</head>
<body>
   <section class="container">
    <section class="dashboard">
    <div class="navbar">
        <h2>Dashboard</h2>
            <br>
            <br>    
            <li><a href="#"><i class="fa fa-fw fa-home"></i>Home</a></li><br><br><br>
            <li><a href="#"><i class="fa fa-fw fa-envelope"></i> Message</a></li><br><br>
            <li><a href="#"><i class="fa fa-fw fa-history"></i> History</a></li> <br><br>
            <li><a href="#"><i class="fa fa-fw fa-file"></i> Tasks</a></li><br><br>
            <li><a href="#"><i class="fa fa-fw fa-users"></i> Communities</a></li><br><br>
            <li><a href="#"><i class="fa fa-fw fa-gear"></i> Settings</a></li><br><br>
            <li><a href="#"><i class="fa fa-fw fa-support"></i> Support</a></li><br><br>
            <li> <a href="#"><i class="fa fa-fw fa-lock"></i> Privacy</a></li><br><br>
    </div>
    </section>
    
   <!-- <section class="top-container"> -->
    <div class="first-row">
        <div class="search-bar">
            <a href="#"><i class="fa fa-fw fa-search"></i></a>
            <input type="search" placeholder="Search...">

        </div>
        <div class="bell-icon">
            <a href="#"><i class="fa fa-fw fa-bell"></i></a>
        </div>
        <div class="github-icon">
            <img src="assests/css/images/github.png"width="25px" height="25px">
            <p>Jayapriya</p>
        </div>
    </div>
    <div class="second-row">
        <div class="profile">
            <img src="assests/css/images/github.png">
        </div>
        <div class="topic">
            <p>Hi there,</p>
            <p>Jayapriya</p>
        </div>
    </div>

    <div class="btn">
        <input type="button" id="new-button" class="new-button" value ="New">
        <input type="button" id="upload-button" class="upload-button" value="Upload">
        <input type="button" id="share-button" class="share-button" value="Share">
    </div>
   <!-- </section> -->
   <div class="middle-container">
    <div class="projects">
        <div class="title">
            <h4> Your projects</h4>
        </div>
    </div>
    <div class="container-1">
        <div class="box-1">
            <h4>Super cool project</h4>
            <p>Loreum ipsum dolor sit amet,consectetur adipiscing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</p>
        </div>
        <div class="box-2">
            <h4>Less cool project</h4>
            <p>Loreum ipsum dolor sit amet,consectetur adipiscing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</p>
        </div>
    </div>
    <div class="container-2">
        <div class="box-3">
            <h4>Impossible App</h4>
            <p>Loreum ipsum dolor sit amet,consectetur adipiscing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</p>
        </div>
        <div class="box-4">
            <h4>Easy Peasy App</h4>
            <p>Loreum ipsum dolor sit amet,consectetur adipiscing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</p>
        </div>
    </div>
    <div class="container-3">
        <div class="box-5">
            <h4>Ad Blocker</h4>
            <p>Loreum ipsum dolor sit amet,consectetur adipiscing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</p>
        </div>
        <div class="box-6">
            <h4>Money Making App</h4>
            <p>Loreum ipsum dolor sit amet,consectetur adipiscing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</p>
    </div>   

</div>
<div class="last-container">
        <div class="heading">
            <p><h3>Announcements</h3></p><br>
        </div>
        <div class="topics">
            <div class="box-topic-1">
                <p><b>Site Maintenance</b></p>
                <p>Loreum ipsum dolor sit amet,consectetur adipiscing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</p>
                <hr>
            </div>
            <div class="box-topic-2">
                <p><b>Community</b></p>
                <p>Loreum ipsum dolor sit amet,consectetur adipiscing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</p>
                <hr>
            </div>
            <div class="box-topic-3">
                <p><b>Updated Privacy policy</b></p>
                <p>Loreum ipsum dolor sit amet,consectetur adipiscing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</p>

            </div>
    </div>
</div>
<div class="user-container">
            <p><h4>People</h4></p>
            <ul>
                <li> @Carlo</li>
                <li> @Jenny</li>
                <li>@jaswanth</li>
            </ul>
</div>
</body>
</html>

body{
    background-color: grey;
    font-family: sans-serif;
    box-sizing: border-box;
}
.navbar h2{
    text-align: center;
    padding-top: 20px;
}.dashboard{
    width: 20%;
    height: 740px;
    background-color: #555; 
    color: #fff;
    justify-content: center;
}
.navbar a {
    float: inherit;
    text-align: center;
    padding: 12px;
    color: white;
    text-decoration: none;
    font-size: 17px;
  } 
  .first-row
  {
    position: relative;
    bottom: 100vh;
    left: 500px;
    /* padding: 20px; */
    height: 5vh;
    /* width: 500vh; */
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .search-bar
  {
    position: relative;
    
    width: 1000vh;
    
    right: 530px;
    
    display: flex;
    
    justify-content: center;
    
     }
  .search-bar input
  {
    border: none;
    padding: 10px;
    width: 50%;
    border-radius: 25px; 
  }
  .search-bar a{
    color: #fff; 
   }
  .bell-icon 
  {
    position: relative;
    right:55%;
    width:100px;
  }
  .bell-icon a{
    color: #fff;
  }
  .github-icon 
  {
    left: 200px;
    display: flex;
  }
 .second-row
  {
    position: relative;
    bottom: 100vh;
    left: 300px;
    /* width:80vw; */
    height: 10vh;
    display: flex;
    align-items: baseline;
    justify-content: left;
  }
  .profile img{
        margin-top: 30px;
        display: flex;
        width: 60px;
        height: 60px;
    }
   .second-row .topic
    {
      position: relative;
      bottom: 5vh;
      left: 5vh;
      
    }
    .profile>img
    { 
        max-width: 100px;
        max-height: 100px;
        margin-left: 30px;
        clip-path: circle();
    }
    .btn
    {
        position: relative;
        bottom: 100vh;
        width:150vw;
        margin: 2px;
        height: 10vh;
        border-radius: 25px;
        left: 1000px;
        
    }
    .middle-container
    {
    box-sizing: border-box;
    position: relative;
    bottom: 122vh;
    left: 300px;

    }
    .title
    {
    margin-top: 180px;
    
    }
    .title h4{
    font-size: 20px;
    position: relative;
    bottom: 60px;
    }
    .container-1 
    {
    display: flex;
    box-sizing: border-box;
    }
    .container-1 .box-1
    {
    position: relative;
    bottom: 80px;
    margin: 15px;
    border: 2px solid;
    border-radius: 10px;
    border-left: 10px solid blueviolet ;
    width: 25%;
    }
    .box-1 img{
    float: right;
    padding: 10px;
    }
    .container-1 .box-2
    {
    position: relative;
    bottom: 80px;
    margin: 15px;
    border: 2px solid;
    border-radius: 10px;
    border-left: 10px solid blueviolet ;
    width: 25%;
    }
    .box-2 img{
    float: right;
    padding: 10px;
    }
    .container-2
    {
    display: flex;
    box-sizing: border-box;

    }
    .container-2 .box-3
    {
    position: relative;
    bottom: 80px;
    margin: 15px;
    border: 2px solid;
    border-radius: 10px;
    border-left: 10px solid blueviolet ;
    width: 25%;
   }
   .box-3 img{
    float: right;
    padding: 10px;
   }
   .container-2 .box-4{
    position: relative;
    bottom: 80px;
    margin: 15px;
    border: 2px solid;
    border-radius: 10px;
    border-left: 10px solid blueviolet ;
    width: 25%;
    }
    .box-4 img{
    float: right;
    padding: 10px;
    }
    .container-3
    {
    display: flex;
    box-sizing: border-box;


    }
    .container-3 .box-5
   {
    position: relative;
    bottom: 80px;
    margin: 15px;
    border: 2px solid;
    border-radius: 10px;
    border-left: 10px solid blueviolet ;
    width: 25%;
    }
    .box-5 img{
    float: right;
    padding: 10px;
    }
    .container-3 .box-6
    {
    position: relative;
    bottom: 80px;
    margin: 15px;
    border: 2px solid;
    border-radius: 10px;
    border-left: 10px solid blueviolet ;
    width: 25%;
    }
     .box-6 img{
    float: right;
    padding: 10px;
    }
    .last-container
   {
    position: relative;
    bottom: 225vh;
    right: 20px;
    float: right;
    box-sizing: border-box;
    width: 25%;
    padding: 15px;
    height: 15px;

   }
   .last-container .topics
   {
    border: 2px solid;
    padding: 15px;
    border-radius: 10px;
    font-size: 11px;

   }
.user-container
{
    position: relative;
    bottom: 160vh;
    left: 360px;
    float: right;
    font-size: larger;
    width: 15%;

}

