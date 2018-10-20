
<html>
<head>
<title>Richards learning website</title>
<link rel="stylesheet" href="styles/styles.css" />
</head>
<body>

<ul>
  <li><a class="active" href="README.md">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="about.html">About</a></li>
</ul>

<h2>What Can JavaScript Do?</h2>

<p>JavaScript can change HTML attribute values.</p>

<p>In this case JavaScript changes the value of the src (source) attribute of an image.</p>

<button onclick="document.getElementById('myImage').src='https://404store.com/2017/12/08/random-pic-14.jpg'">Turn on the light</button>

<img id="myImage" src="XfG4cdf.jpg" style="width:100px">

<button onclick="document.getElementById('myImage').src='XfG4cdf.jpg'">Turn off the light</button>

</body>
</html>
