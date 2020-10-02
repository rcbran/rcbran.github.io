.large-header {
   position: relative;
   width: 100%;
   background: #111;
   overflow: hidden;
   background-size: cover;
   background-position: center center;
   z-index: 1;
}

.demo .large-header {
   background-image: url("https://www.storeautomator.com/wp-content/uploads/2019/12/AdobeStock_274929184-scaled.jpeg");
}

.main-title {
   position: absolute;
   margin: 0;
   padding: 0;
   color: ##000000;
   text-align: center;
   top: 50%;
   left: 50%;
   -webkit-transform: translate3d(-50%, -50%, 0);
   transform: translate3d(-50%, -50%, 0);
}

.boxes {
   position: absolute;
   margin: 0;
   padding: 0;
   color: #FF0000;
   text-align: center;
   top: 50%;
   left: 50%;
   -webkit-transform: translate3d(-50%, -50%, 0);
   transform: translate3d(-50%, -50%, 0);
}

.demo .main-title {
   text-transform: uppercase;
   font-size: 4.2em;
   letter-spacing: 0.1em;
}

.main-title .thin {
   font-weight: 200;
}

@media only screen and (max-width: 768px) {
   .demo .main-title {
      font-size: 3em;
   }
}



<div class="container demo">
   <div class="content">
      <div id="large-header" class="large-header">
         <canvas id="demo-canvas"></canvas>
         <h1 class="main-title"><span class="thin">HTB</span> Writeups </br></br> </h1>
   
         <h1 class="boxes"><span class="thin"> </br> </br> </br> </br> </br>
            <a href="https://rc-work.github.io/remote.html">Remote </a>                </br>
            <a href="https://rc-work.github.io/sneakymailer.html">SneakyMailer</a>     </br>
            <a href="https://rc-work.github.io/doctor.html">Doctor</a> </h1>           </br>

      </div>
   </div>
</div>   
