<!DOCTYPE HTML>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@900&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="style.css">

  </head>
<body>
        
<section class="header">
  <nav>

    <div class="title">
          <img src="space-shuttle-solid.svg">
        </div>
        <div class="space">
          <h4>SPACE EXPLORATION.NET</h4>
      </div>
     </div>

        


 

      

           
  </nav>
  

  <div class="right-col">
    <p>Click here to hear some music</p>
    <img src="play.png" id="icon">
  </div>
  
  <audio id="mySong">
  <source src="MOSKAU.mp3" type="audio/mp3">
  </audio>
  
  <script>
   var mySong = document.getElementById('mySong');
   var icon = document.getElementById('icon');
  
   icon.onclick = function(){
     if(mySong.paused){
       mySong.play();
       icon.src="pause.png";
     }else{
       mySong.pause();
       icon.src="play.png";
     }
   }
  </script>
</section>




<h3>Launch of Apollo 11</h3>
<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/o4OBKOlgmfo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>



  <div class="text-content">
    <h2><span></span></h2>

    </div>

</div>









<section class="course">
  <centre>
        <h1>Main Site</h1>
      
  </centre>
        


          <div class="course-col">
            <h3>Visit Our Main Site</h3>
              <a href="SIE.html" class="hero-btn">Click here to jump to main site!!</a>
          </div>


</section>






<section class="footer">


  <div class="footer-col">
  <IMG SRC ="made in india.png"/>
  </div>
  <div class="space">
    <h4>©SPACE EXPLORATION.NET</h4>
  </div>
</div>



</body>
</html>
