<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Digvijay Vapilkar | Portfolio</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <link rel="stylesheet" href="style.css">
</head>
<body data-spy="scroll" data-target=".navbar" data-offset="70">

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
  <a class="navbar-brand" href="https://www.linkedin.com/in/digvijay-vapilkar-651486294/">Digvijay Vapilkar</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
      <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
      <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
      <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
    </ul>
  </div>
</nav>

<!-- Hero Section -->
<header class="hero text-white text-center">
  <div class="container">
    <img src="images/Profile_photo.jpeg" id="profilePhoto" class="rounded-circle mb-3" width="150" alt="Digvijay Vapilkar" style="cursor: pointer;">
    <h1 class="display-4">Hi, I'm Digvijay Vapilkar</h1>
    <p class="lead">Web Developer | Programmer | Tech Enthusiast</p>
    <a href="images/resume/Digvijay_Vapilkar_9309475959.pdf" target="_blank" class="btn btn-info mt-2 text-white">You can see my resume</a>
  </div>
</header>

<!-- Fullscreen Image Modal -->
<div id="popup" class="popup-backdrop" onclick="closePopup()">
  <div class="popup-box" onclick="event.stopPropagation();">
    <img src="images/Profile_photo.jpeg" class="img-fluid rounded" alt="Profile Enlarged">
  </div>
</div>

<!-- About Section -->
<section id="about" class="py-5 bg-light">
  <div class="container text-center">
    <h2 style="border: 1px solid gray; background-color: aquamarine;">About Me</h2>
    <p>I’m a dedicated and motivated B.Tech Computer Science student with a strong interest in web development, UI design, and backend programming...</p>
  </div>
</section>

<!-- Education Section -->
<section id="education" class="py-5">
  <div class="container text-center">
    <h2 style="border: 1px solid gray; background-color: aquamarine;">Education</h2>
    <p><strong>B.Tech in Computer Science and Engineering</strong><br>D Y Patil Agriculture and Technical University Talsande<br>2021 - 2025<br>Percentage: 85.63%</p>
    <p><strong>HSC</strong><br>Sau S M Lohia jr College Kolhapur<br>Passed: 2021<br>Percentage: 74.67%</p>
    <p><strong>SSC</strong><br>Arya Public School Gaganbawada<br>Passed: 2019<br>Percentage: 79.60%</p>
  </div>
</section>

<!-- Projects Section -->
<section id="projects" class="py-5">
  <div class="container">
    <h2 class="text-center" style="border: 1px solid gray; background-color: aquamarine;">Projects</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="card mb-4 shadow-sm">
          <img src="images/food.png" class="card-img-top" alt="Project 1">
          <div class="card-body">
            <h5>1. Food Ordering Website</h5>
            <p class="card-text">A responsive food ordering platform with RESTful APIs and PHP backend. [<a href="https://github.com/Digu45/Food_Ordering_Website" target="_blank">GitHub</a>]</p>
          </div>
        </div>
      </div>
      <!-- More projects... -->
    </div>
  </div>
</section>

<!-- Skills Section -->
<section id="skills" class="bg-light py-5">
  <div class="container text-center">
    <h2 style="border: 1px solid gray; background-color: aquamarine;">Skills</h2>
    <div class="row">
      <div class="col-md-2 mb-4"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" alt="HTML"><div>HTML</div></div>
      <div class="col-md-2 mb-4"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" alt="CSS"><div>CSS</div></div>
      <div class="col-md-2 mb-4"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" alt="JavaScript"><div>JavaScript</div></div>
      <!-- More skills... -->
    </div>
  </div>
</section>

<!-- Contact Section -->
<section id="contact" class="py-5">
  <div class="container">
    <h2 class="text-center" style="border: 1px solid gray; background-color: aquamarine;">Contact Me On</h2>
    <div class="text-center">
      <a href="mailto:diguvapilkar45@gmail.com" target="_blank" class="mx-2"><img src="https://img.icons8.com/fluency/48/000000/new-post.png" width="30" alt="Email"></a>
      <a href="https://www.linkedin.com/in/digvijay-vapilkar-651486294/" target="_blank" class="mx-2"><img src="https://img.icons8.com/fluency/48/linkedin.png" width="30" alt="LinkedIn"></a>
      <a href="https://github.com/Digu45" target="_blank" class="mx-2"><img src="https://img.icons8.com/ios-glyphs/30/000000/github.png" width="30" alt="GitHub"></a>
      <a href="https://www.instagram.com/dig_vapilkar_45/" target="_blank" class="mx-2"><img src="https://img.icons8.com/fluency/48/instagram-new.png" width="30" alt="Instagram"></a>
    </div>
  </div>
</section>

<!-- JavaScript -->
<script>
  const profilePhoto = document.getElementById("profilePhoto");
  const popup = document.getElementById("popup");

  profilePhoto.onclick = function () {
    popup.style.display = "flex";
  }

  function closePopup() {
    popup.style.display = "none";
  }
</script>

<!-- Bootstrap Scripts -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.2/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
