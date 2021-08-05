<!DOCTYPE html>
<html lang="en">
<head>
<title>Krish's Bio Data</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Style the body */
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}
img {
  border-radius: 50%;
}

/* Header/ Title */
.header {
  padding: 80px;
  text-align: center;
  background: #00ff00;
  color: white;
}

/* Increase the font size of the heading by 40px */
.header h1 {
  font-size: 40px;
}

/* Navbar - toggles between relative and fixed, depending on the scroll position. */
.navbar {
  overflow: hidden;
  background-color: #333;
  position: sticky;
  position: -webkit-sticky;
  top: 0;
}


/* Main column */
.main {   
  -ms-flex: 70%; /* IE10 */
  flex: 70%;
  background-color: white;
  padding: 20px;
}

/* Writing Part 001 */
.fakeimg {
  background-color: Orange;
  width: 100%;
  padding: 20px;
}
div {
  border: 1px solid black;
  margin-top:0px;
  margin-bottom: 50px;
  margin-right: 0px;
  margin-left: 0px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}
div {
  border: 1px solid black;
  margin-top:0px;
  margin-bottom: 50px;
  margin-right: 0px;
  margin-left: 0px;
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}
</style>
<style>
body {
  background-color: #03fcf4;
}
</style>
</head>
<body>
<div>
   <div class="header">
  <img src="E:\Pics\DCIM Phone/20191126_083149.jpg" alt="Simply Easy Learning" width="200"
         height="80"><h2><p style="color:blue">Krish Log</p><h2>
  <p>This is Krish's bio data website.</p>
</div>


<marquee behavior="scroll" direction="right" scrollamount="12">Hello Guys. You are seeing the bio data of Krish Log. Enjoy</marquee>

    <h2><center>Short Biography & Profession <center></h2>
    
    <div class="fakeimg" style="height:100px;"><strong>Hello. I am Krish Log. I am 11 years old right now and studing in 6th Grade. My Profession - My profession is coding and programming and I have coded games apps webpages and more. I have made my own website and app. 
 <strong></div>
   
    <br>
    <h2><center>Educational Qualifications<center></h2>
    
    <div class="fakeimg" style="height:100px;">Studing in grade 6. </div>
    
	<br>
	<h2><center>Contact Info<center></h2>
    
    <div class="fakeimg" style="height:100px;">Outlook Mail - genius542@outlook.com </div>
  </div>
</div>

<div class="footer">
  <h2>Thanks </h2>
    <button onmouseover="javascript:alert('CLICK!!. To Message Me If your have any questions')">CLICK!!. To Message Me If your have any questions</button>
    </div>

</div>

</body>
</html>
