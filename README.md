<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>My Project</title>
<style>
body {
  font-family: Arial;
  background: #111;
  color: white;
  text-align: center;
  padding: 40px;
}

.button {
  display: inline-block;
  padding: 14px 26px;
  margin: 10px;
  border-radius: 12px;
  background: #0077ff;
  color: white;
  font-size: 20px;
  text-decoration: none;
  transition: 0.3s;
}

.button:hover {
  background: #0055cc;
  transform: scale(1.07);
}

.box {
  width: 260px;
  margin: 40px auto;
  padding: 20px;
  border-radius: 16px;
  background: linear-gradient(135deg, #9C27B0, #673AB7);
  animation: float 3s infinite ease-in-out;
}

@keyframes float {
  50% { transform: translateY(-12px); }
}
</style>
</head>
<body>

<h1>🚀 My Animated UI</h1>

<a class="button" href="#">Button 1</a>
<a class="button" href="#">Button 2</a>
<a class="button" href="#">Button 3</a>

<div class="box">
  <h2>Animated Card</h2>
  <p>Floating, glowing component.</p>
</div>

</body>
</html>
