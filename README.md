<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <!-- Link to Bootstrap and Tailwind -->
  <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.0.2/dist/tailwind.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg bg-gray-800 text-white">
  <div class="container">
    <a class="navbar-brand text-white" href="#">My Portfolio</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
        <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<section id="hero" class="hero bg-blue-500 text-white py-20 text-center">
  <h1 class="text-4xl font-bold">Hello, I'm Monika</h1>
  <p class="mt-4">A frontend Web Developer with a passion for creating beautiful and functional websites</p>
</section>

<!-- About Section -->
<section id="about" class="about py-20">
  <div class="container text-center">
    <h2 class="text-3xl font-bold mb-6">About Me</h2>
    <p class="max-w-2xl mx-auto">I'm Monika, a second-year B.Tech student specializing in Computer Science and Engineering with a focus on Artificial Intelligence and Machine Learning at MOHAN BABU University.
I'm currently learning Full stack development with specialization in 4.0 technologies. While I don't yet have formal certifications. My goal is to master full-stack development.I'm eager to connect with professionals and mentors in the tech industry to share knowledge and collaborate.</p>
  </div>
</section>

<!-- Projects Section -->
<section id="projects" class="projects py-20 bg-gray-100">
  <div class="container text-center">
    <h2 class="text-3xl font-bold mb-6">My Projects</h2>
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="project1.jpg" class="card-img-top" alt="Project 1">
          <div class="card-body">
            <h5 class="card-title">READY-2-RESCUE EMERGENCY HUB</h5>
            <p class="card-text">Ready to rescue is my first ever project , which has been done by the mentorship of NxtWave CCBP academy using Generative-AI-tools.
            I tried to develop a website with which anyone in emergency would be able to have a rescue. </p>
            <a href="#https://drive.google.com/file/d/1gmb-rY_YnMhqx1K92M4I-XD4iELvXNFT/view" class="btn btn-primary">View Project</a>
          </div>
        </div>
      </div>
      <!-- Repeat for more projects -->
    </div>
  </div>
</section>

<!-- Contact Section -->
<section id="contact" class="contact py-20">
  <div class="container text-center">
    <h2 class="text-3xl font-bold mb-6">Contact Me</h2>
    <form action="https://formspree.io/f/{your_form_id}" method="POST" class="max-w-lg mx-auto">
      <input type="text" name="name" class="form-control mb-3" placeholder="MONIKA GK" required>
      <input type="email" name="email" class="form-control mb-3" placeholder="gkmonika01@gmail.com" required>
      <textarea name="message" rows="4" class="form-control mb-3" placeholder="STAY CURIOUS" required></textarea>
      <button type="submit" class="btn btn-primary">Send Message</button>
    </form>
  </div>
</section>

<!-- Footer -->
<footer class="bg-gray-800 text-white text-center py-4">
  <p>&copy; 2024 My Portfolio</p>
</footer>

</body>
</html>
