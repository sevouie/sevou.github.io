<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Fullscreen GIF Style Video</title>
<style>
html, body {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  overflow: hidden;
}

video {
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  object-fit: cover;
}
</style>
</head>
<body>

<video autoplay loop muted playsinline>
  <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
</video>

</body>
</html>

