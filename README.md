<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shehan | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
body{background:#0f172a;color:#e2e8f0}

header{padding:20px 50px;display:flex;justify-content:space-between;align-items:center;background:#020617}
header h1{color:#38bdf8}
nav a{margin:0 15px;color:#e2e8f0;text-decoration:none}

.hero{padding:80px 50px;text-align:center}
.hero h2{font-size:40px;color:#38bdf8}
.hero p{margin-top:15px}

.btn{margin-top:20px;display:inline-block;padding:10px 20px;background:#6366f1;color:#fff;border-radius:8px;text-decoration:none}

.section{padding:60px 50px}
.section h2{color:#38bdf8;margin-bottom:20px}

.skills span{display:inline-block;background:#1e293b;margin:5px;padding:8px 12px;border-radius:8px}

.card{background:#1e293b;padding:20px;border-radius:12px;margin-top:10px}

footer{text-align:center;padding:20px;background:#020617;margin-top:40px}

input,textarea{width:100%;padding:10px;margin:10px 0;border:none;border-radius:6px}
button{padding:10px 20px;background:#6366f1;border:none;color:#fff;border-radius:6px}
</style>
</head>

<body>

<header>
<h1>Shehan</h1>
<nav>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero">
<img src="profile.jpg" alt="Shehan" style="width:150px;height:150px;border-radius:50%;object-fit:cover;border:4px solid #38bdf8;box-shadow:0 0 20px #38bdf8;margin-bottom:20px;">
<h2>Nipuna Shehan</h2>
<p>Computer Science Student | Aspiring Software Engineer</p>
<a class="btn" href="#">Download CV</a>
</section>

<section class="section" id="about">
<h2>About Me</h2>
<p>I am Rajapaksha Pathiranage Nipuna Shehan Nethmina, a Computer Science student at IIT. I enjoy building responsive web applications and improving my skills in modern technologies.</p>
</section>

<section class="section" id="skills">
<h2>Skills</h2>
<div class="skills">
<span>HTML</span>
<span>CSS</span>
<span>JavaScript</span>
<span>Java</span>
<span>Python</span>
<span>React</span>
<span>Bootstrap</span>
<span>MySQL</span>
</div>
</section>

<section class="section" id="contact">
<h2>Contact</h2>
<form>
<input type="text" placeholder="Your Name">
<input type="email" placeholder="Your Email">
<textarea placeholder="Message"></textarea>
<button>Send</button>
</form>
</section>

<footer>
<p>© 2026 Shehan | GitHub: shehanrajapaksha337</p>
</footer>

</body>
</html>
