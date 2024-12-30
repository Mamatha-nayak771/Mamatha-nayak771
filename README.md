- <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mamatha Dharavath - Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Mamatha Dharavath</h1>
    <p>Aspiring Software Developer | AI Enthusiast</p>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#certifications">Certifications</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>
      I am Mamatha Dharavath, a Computer Science and Engineering student at Malla Reddy Institute of 
      Engineering & Technology, Hyderabad. With a passion for software development and AI, I aim to build 
      innovative solutions for real-world problems. Graduation expected in 2025, CGPA: 7.68.
    </p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li><strong>Languages:</strong> Python, C, C++, React JS, HTML</li>
      <li><strong>Databases:</strong> MySQL</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Detection on Cyberbullying on Social Media</h3>
      <p>
        Developed a website using HTML, CSS, and Python. Leveraged machine learning and natural language 
        processing to detect harmful content in real-time, ensuring safer online environments.
      </p>
    </div>
    <div class="project">
      <h3>AI Medical Chatbot for Infectious Disease Prediction</h3>
      <p>
        Created a chatbot using Python, JavaScript, HTML, and CSS. Analyzes symptoms and predicts diseases, 
        providing remote healthcare access and improving accuracy with advanced algorithms.
      </p>
    </div>
  </section>

  <section id="certifications">
    <h2>Certifications</h2>
    <ul>
      <li>Build Your Own Static Website - Nxtwave</li>
      <li>Build Your Own Responsive Website - Nxtwave</li>
      <li>Introduction to Databases - Nxtwave</li>
      <li>Software Engineering Job Simulation - Forage</li>
      <li>Advanced C++ Course Online - Skillup</li>
      <li>Introduction to Artificial Intelligence - Skillup</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: mamatha.dharavath@example.com</p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/mamatha-dharavath" target="_blank">linkedin.com/in/mamatha-dharavath</a></p>
  </section>

  <footer>
    <p>© 2024 Mamatha Dharavath. All rights reserved.</p>
  </footer>
</body>
</html>
styles.css
css
Copy code
/* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  color: #333;
  background: #f4f4f4;
}

header {
  background: url('header-bg.jpg') no-repeat center center/cover;
  color: white;
  text-align: center;
  padding: 3rem 0;
}

header h1 {
  margin: 0;
  font-size: 3rem;
}

header p {
  font-size: 1.5rem;
}

nav ul {
  display: flex;
  justify-content: center;
  list-style: none;
  background: #333;
  margin: 0;
  padding: 0;
}

nav ul li {
  margin: 0 1rem;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-size: 1.1rem;
}

section {
  padding: 2rem;
  margin: auto;
  max-width: 800px;
  background: white;
  margin-bottom: 1rem;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

section h2 {
  color: #444;
  margin-top: 0;
}

footer {
  text-align: center;
  padding: 1rem;
  background: #333;
  color: white;
}

.project {
  margin-bottom: 1.5rem;
}

/* Responsive Design */
@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
  }

  nav ul li {
    margin: 0.5rem 0;
  }
}
Deployment
Save the files (index.html and styles.css) in a folder.
Add a background image named header-bg.jpg in the same folder or link a URL to the background.
Push the folder to a GitHub repository.
Deploy via GitHub Pages, Netlify, or Vercel.
Let me know if you'd like further customization!






















