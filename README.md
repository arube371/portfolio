# portfolio
portfolio/
 ┣ index.html
 ┣ style.css
 ┣ script.js
 ┗ images/
      ┗ profile.jpg

      <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Home Section -->
  <header id="home">
    <img src="images/profile.jpg" alt="Profile Picture" class="profile-pic">
    <h1>Your Name</h1>
    <p>Upcoming IT Professional | Web & Mobile App Development</p>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      I am a BSIT student specializing in Web and Mobile Application Development.  
      I am passionate about coding, solving problems, and building impactful applications.
    </p>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Student Registration System</h3>
      <p>A database-driven web app for managing student registration and exam results.</p>
    </div>
    <div class="project">
      <h3>Health Centre Website</h3>
      <p>A responsive HTML & CSS website built for Patongo Health Centre IV.</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>075366444</h2>
    <ul>
      <li>Email: <a href="mailto:lawrencebalenteopio@gmail.com">lawrenceopiobalente @gmail.com</a></li>
      <li>GitHub: <a href="https://github.com/kideganono lawrence" target="_blank">github.com/kideganono lawrence</a></li>
      <li>LinkedIn: <a href="https://linkedin.com/in/kideganono lawrence" target="_blank">linkedin.com/in/kideganono lawrence</a></li>
    </ul>
  </section>

  <footer>
    <p>© 2025 KIDEGANONO LAWRENCE. NO RETREAT NO SURRENDOR.</p>
  </footer>
  
  <script src="script.js"></script>


css
  body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  background: flat;
  color: green;
}

header {
  text-align: center;
  background: normal;
  color: white;
  padding: 40px 20px;
}

.profile-pic {
  width: 150px;
  border-radius: 50%;
}

section {
  padding: 40px 20px;
  max-width: 800px;
  margin: auto;
}

h2 {
  color: yellow green;
}

.project {
  background: flat;
  margin: 15px 0;
  padding: 15px;
  border-left: 5px solid;
}

#contact ul {
  list-style: none;
  padding: 0;
}

#contact li {
  margin: 10px 0;
}

footer {
  text-align: center;
  padding: 20px;
  background: normal;
  color: white;
}


// Simple alert when page loads
window.onload = () => {
  console.log("Welcome to my portfolio website!");
};

</body>
</html>
