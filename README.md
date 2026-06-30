<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NayePankh Foundation</title>

<link rel="stylesheet" href="style.css">

<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

</head>
<body>

<div class="watermark">NayePankh Foundation</div>

<header>

<h1>NayePankh Foundation</h1>

<p>Empowering Youth • Educating Children • Creating Better Futures</p>

<button id="darkBtn">
<i class="fa-solid fa-moon"></i> Dark Mode
</button>

</header>

<nav>

<a href="#about">About</a>

<a href="#mission">Mission</a>

<a href="#programs">Programs</a>

<a href="#volunteer">Volunteer</a>

<a href="#contact">Contact</a>

</nav>

<section class="hero">

<h2>Together We Can Change Lives</h2>

<p>
NayePankh Foundation works towards education,
skill development, community welfare and empowering
young minds across India.
</p>

<a href="#volunteer" class="btn">Become a Volunteer</a>

</section>

<section id="about" class="card">

<h2>About Us</h2>

<p>

NayePankh Foundation is committed to creating
opportunities for underprivileged children and youth.
Our initiatives focus on education, awareness,
skill development and social welfare.

</p>

</section>

<section id="mission" class="card">

<h2>Mission & Vision</h2>

<div class="grid">

<div>

<h3>Mission</h3>

<p>

Provide equal opportunities through education,
technology and community support.

</p>

</div>

<div>

<h3>Vision</h3>

<p>

Build a society where every individual can
learn, grow and succeed regardless of background.

</p>

</div>

</div>

</section>

<section id="programs" class="card">

<h2>Our Programs</h2>

<div class="cards">

<div class="box">

<i class="fa-solid fa-book-open"></i>

<h3>Education</h3>

<p>Free learning support and mentoring.</p>

</div>

<div class="box">

<i class="fa-solid fa-laptop-code"></i>

<h3>Digital Skills</h3>

<p>Basic computer and coding workshops.</p>

</div>

<div class="box">

<i class="fa-solid fa-hand-holding-heart"></i>

<h3>Community Service</h3>

<p>Social awareness and volunteer activities.</p>

</div>

</div>

</section>

<section id="volunteer" class="card">

<h2>Become a Volunteer</h2>

<form>

<input type="text" placeholder="Full Name" required>

<input type="email" placeholder="Email" required>

<textarea placeholder="Why do you want to volunteer?"></textarea>

<button type="submit">Submit</button>

</form>

</section>

<section id="contact" class="card">

<h2>Contact</h2>

<p>

📍 India

</p>

<p>

📧 info@nayePankh.org

</p>

<p>

📞 +91-9876543210

</p>

</section>

<footer>

<p>

© 2026 NayePankh Foundation | Designed by Bhavika Tewari

</p>

</footer>

<script src="script.js"></script>

</body>
</html>



*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
scroll-behavior:smooth;
}

body{
background:linear-gradient(135deg,#4facfe,#00f2fe,#43e97b);
color:#222;
transition:0.4s;
}

/* Watermark */
.watermark{
position:fixed;
top:45%;
left:50%;
transform:translate(-50%,-50%) rotate(-30deg);
font-size:70px;
font-weight:bold;
color:rgba(255,255,255,0.08);
pointer-events:none;
z-index:0;
}

header{
text-align:center;
padding:50px 20px;
color:white;
}

header h1{
font-size:45px;
margin-bottom:10px;
}

header p{
font-size:20px;
margin-bottom:20px;
}

#darkBtn{
padding:12px 20px;
background:#fff;
color:#333;
border:none;
border-radius:30px;
cursor:pointer;
font-size:16px;
transition:0.3s;
}

#darkBtn:hover{
background:#222;
color:white;
}

nav{
display:flex;
justify-content:center;
flex-wrap:wrap;
gap:20px;
padding:15px;
background:white;
box-shadow:0 2px 10px rgba(0,0,0,.2);
position:sticky;
top:0;
z-index:100;
}

nav a{
text-decoration:none;
font-weight:bold;
color:#0077ff;
}

.hero{
padding:80px 20px;
text-align:center;
color:white;
animation:fadeIn 1.5s;
}

.hero h2{
font-size:40px;
margin-bottom:20px;
}

.hero p{
max-width:700px;
margin:auto;
line-height:1.8;
font-size:18px;
}

.btn{
display:inline-block;
margin-top:30px;
padding:15px 30px;
background:#ff9800;
color:white;
text-decoration:none;
border-radius:30px;
font-weight:bold;
transition:.3s;
}

.btn:hover{
background:#ff5722;
transform:scale(1.05);
}

.card{
background:white;
width:90%;
max-width:1000px;
margin:40px auto;
padding:30px;
border-radius:20px;
box-shadow:0 10px 25px rgba(0,0,0,.2);
animation:slideUp 1s;
}

.card h2{
text-align:center;
margin-bottom:20px;
color:#0077ff;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.box{
background:#f7f7f7;
padding:20px;
border-radius:15px;
text-align:center;
transition:.3s;
}

.box:hover{
transform:translateY(-10px);
background:#e3f2fd;
}

.box i{
font-size:40px;
color:#ff9800;
margin-bottom:15px;
}

form{
display:flex;
flex-direction:column;
gap:15px;
}

input,textarea{
padding:15px;
border:1px solid #ccc;
border-radius:10px;
font-size:16px;
}

textarea{
height:120px;
resize:none;
}

form button{
padding:15px;
border:none;
background:#0077ff;
color:white;
font-size:18px;
border-radius:10px;
cursor:pointer;
}

form button:hover{
background:#0056d2;
}

footer{
text-align:center;
padding:30px;
color:white;
font-weight:bold;
}

/* Dark Mode */
.dark{
background:#111;
color:white;
}

.dark .card{
background:#222;
color:white;
}

.dark nav{
background:#333;
}

.dark nav a{
color:white;
}

.dark input,
.dark textarea{
background:#333;
color:white;
border:1px solid #555;
}

@keyframes fadeIn{
from{opacity:0;}
to{opacity:1;}
}

@keyframes slideUp{
from{
transform:translateY(40px);
opacity:0;
}
to{
transform:translateY(0);
opacity:1;
}
}

@media(max-width:768px){

header h1{
font-size:32px;
}

.hero h2{
font-size:30px;
}

.watermark{
font-size:40px;
}







// Dark Mode Toggle
const darkBtn = document.getElementById("darkBtn");

darkBtn.addEventListener("click", function () {
    document.body.classList.toggle("dark");

    if (document.body.classList.contains("dark")) {
        darkBtn.innerHTML = "☀️ Light Mode";
    } else {
        darkBtn.innerHTML = "🌙 Dark Mode";
    }
});

// Volunteer Form
const form = document.querySelector("form");

form.addEventListener("submit", function (e) {
    e.preventDefault();

    alert("🎉 Thank you for volunteering with NayePankh Foundation!");

    form.reset();
});

// Smooth Fade-in Animation
const cards = document.querySelectorAll(".card");

const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.style.opacity = "1";
            entry.target.style.transform = "translateY(0)";
        }
    });
});

cards.forEach(card => {
    card.style.opacity = "0";
    card.style.transform = "translateY(50px)";
    card.style.transition = "all 0.8s ease";
    observer.observe(card);
});

// Navigation Active Effect
const links = document.querySelectorAll("nav a");

links.forEach(link => {
    link.addEventListener("click", () => {
        links.forEach(l => l.style.color = "");
        link.style.color = "#ff5722";
    });
});

}





