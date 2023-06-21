# SocialNetworks.
Design of Social Networks.
html:
<!DOCTYPE html>  
 <html lang="en">  
  <head>  
   <meta charset="UTF-8" />  
   <meta http-equiv="X-UA-Compatible" content="IE=edge" />  
   <meta name="viewport" content="width=device-width, initial-scale=1.0" />  
   <title>Mis Redes Profesionales</title>  
   <link rel="stylesheet" href="misredesprof.css" />  
   
<?php
                                    
                     /* Developed by Oswaldo Jesús Marín Pagés*/
                    

?>

  </head>  
  <body>  
   <main>  
    <button>  
     <ion-icon name="logo-facebook"></ion-icon>  
    </button>  
    <button>  
     <ion-icon name="logo-twitter"></ion-icon>  
    </button>  
    <button>  
     <ion-icon name="logo-instagram"></ion-icon>  
    </button>  
    <button>  
     <ion-icon name="logo-youtube"></ion-icon>  
    </button>  
    <button>  
     <ion-icon name="logo-github"></ion-icon>  
    </button>    
   </main>     
   <div class="cursor cursor--large"></div>  
   <div class="cursor cursor--small"></div>  
   <!-- gsap and icon link -->     
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.1.1/gsap.min.js"></script>  
    <script src="https://unpkg.com/ionicons@5.0.0/dist/ionicons.js"></script>  
    <script src="barraiconos.js"></script>  
 </html>  

 css:
 * {  
  box-sizing: border-box;  
  margin: 0;  
  padding: 0;  
 }
 
 body {  
  width: 100%;  
  height: 100vh;  
  display: flex;  
  justify-content: center;  
  align-items: center;  
  overflow: hidden;  
  background: #000000;  
  cursor: none;  
 }  
 
 .cursor {  
  width: var(--size);  
  height: var(--size);  
  border-radius: 50%;  
  position: absolute;  
  left: 0;  
  top: 0;  
  pointer-events: none;  
  z-index: 100;  
 }  
 
  .cursor--large {  
  --size: 40px;  
  border: 1px solid #ff3c3c;  
 }  
 .cursor--small {  
  --size: 10px;  
  background: #ff3c3c;  
  transform: translate(-50%, -50%);  
 }  
 
 main {  
  display: flex;  
  flex-wrap: wrap;  
  justify-content: center;  
 }  
 
 main button {  
  --size: 60px;  
  border-color: blue;
  border-radius: 30px;  
  min-width: var(--size);  
  min-height: var(--size);  
  display: flex;  
  justify-content: center;  
  align-items: center;  
  font-size: 1.5rem;  
  background: rgba(255, 255, 255, 0.08);  
  color: orange;  
  transition: background 200ms ease, color 200ms ease;  
  cursor: none;  
 }  
 
 main:hover button {  
  background: orange;  
  color: #fff;  
 } 
 
 main:hover button:hover {  
  color: blue;  
 } 
 
 .support {  
  position: absolute;  
  right: 10px;  
  bottom: 10px;  
  padding: 10px;  
  display: flex;  
 }

.support a {  
  margin: 0 10px;  
  color: #fff;  
  font-size: 1.8rem;  
  backface-visibility: hidden;  
  transition: all 150ms ease;  
 }   
 
 .support a:hover {  
  transform: scale(1.1);  
 }
