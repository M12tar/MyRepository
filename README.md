<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <link rel="stylesheet" href="style.css">
  <title>Frontend Mentor | QR code component</title>
  
  <!--================================================ style ================================================-->
  
  
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@700&display=swap');
body
{
    font-family: 'Outfit', sans-serif;
    background-color: hsl(212, 45%, 89%);
    /* display: flex;
    align-items: center; */
    font-size: 15px;
}
.container
{
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-height: 95vh;
    align-items: center;
    margin: 0 auto;
    height: auto;
}
.card
{
    background-color: hsl(0, 0%, 100%);
    border-radius: 15px;
    width: 240px;
    padding: 15px;
    text-align: center;
    box-shadow: 2px 1px 30px  rgba(114, 114, 114, 0.3);
}
.card img
{   
    border-radius: 10px;
    width: 240px; height: 240px;
}
.text h3
{
    color: hsl(218, 44%, 22%);
}
.text p
{
    color: hsl(220, 15%, 55%);
    
}
.attribution 
{ 
    font-size: 11px;
    text-align: center;
    margin-bottom: 20px;
 
 }
.attribution a
 { 
    color: hsl(228, 45%, 44%);
 }
  </style>
<!--================================================ End style ================================================-->
</head>
  
  
<body>
  <div class="container">
    <div class="card">
      <img src="images/image-qr-code.png" alt="">
      <div class="text">
        <h3>Improve your front-end skills by building projects</h3>
        <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
      </div>
    </div>
  </div>
    <div class="attribution">
     Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
     Coded by <a href="mailTo:mohamed12tar@gmail.com">mohamed tarfous</a>.
     </div>
</body>
</html>
