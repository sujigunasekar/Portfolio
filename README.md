# Ex01 Portfolio
## Date:04.03.25

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
### HTML
De
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Suji G - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Suji G</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#internships">Internships</a></li>
                <li><a href="#achievements">Achievements</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <img src="suji.jpeg" alt="Suji G" class="profile-pic">
        <p>I am a passionate and highly motivated Artificial Intelligence and Data Science student with a strong foundation in programming, web technologies, and problem-solving. I enjoy tackling new challenges and leveraging my skills in data analysis, machine learning, software development, and web technologies to create impactful solutions.</p>
        <p><strong>Resume:</strong> <a href="suji_resume1.pdf" target="_blank">Download Here</a></p>
    </section>

    <section id="education">
        <h2>Education</h2>
        <p><strong>Saveetha Engineering College</strong></p>
        <p>B.Tech in Artificial Intelligence and Data Science (2022 - 2026)</p>
        <p>CGPA: 8.1</p>
        <p><strong>Sai Matriculation Higher Secondary School</strong></p>
        <p>HSC - 86% (2022)</p>
        <p>SSLC - 89% (2020)</p>
    </section>

    <section id="skills">
        <h2>Technical Skills</h2>
        <ul>
            <p>Machine Learning & Data Analysis</p>
            <p>Version Control (Git & GitHub)</p>
            <p>Web Development (HTML, CSS, JavaScript, Node.js)</p>
            <p>Programming Languages: Python, C, Java, SQL</p>
            <p>Tools & Libraries: TensorFlow, OpenCV</p>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>🎵 Music Player</h3>
            <p>Developed a web-based music player using HTML, CSS, JavaScript, and Node.js, enabling smooth audio playback and playlist management.</p>
        </div>
        <div class="project">
            <h3>📸 Cam-Detection</h3>
            <p>Built a real-time hidden spy camera detection system using computer vision techniques like SSD and image processing.</p>
        </div>
        <div class="project">
            <h3>🍔 Food Delivery Prediction</h3>
            <p>Designed a Machine Learning model to predict food delivery time based on distance, traffic, and order details. Used regression algorithms to improve accuracy.</p>
        </div>
    </section>

    <section id="internships">
        <h2>Internships</h2>
        <div class="internship">
            <h3>Edify Techno Solutions - Pet Store Development</h3>
            <p>Developed and designed a pet store website using HTML, CSS, and JavaScript, focusing on interactivity and user experience.</p>
        </div>
        <div class="internship">
            <h3>Arjun Vision Technologies - Music Player</h3>
            <p>Created a web-based music player with Node.js, HTML, and JavaScript, featuring audio playback controls and playlist management.</p>
        </div>
    </section>

    <section id="achievements">
        <h2>Achievements</h2>
        <ul>
            <p>🏆 Amazon AIML Challenge: Participated in Amazon's Machine Learning challenge, applying ML models to solve real-life business problems.</p>
            <p>📊 IBM Z Datathon 2024: Engaged in a data science competition, leveraging IBM Z technology to analyze datasets and develop solutions.</p>
            <p>📜 Certifications:
                <ul>
                    <p>Deep Learning TensorFlow for AI, ML, DL, NLP, CNN</p>
                    <p>Interactivity with JavaScript (Coursera)</p>
                    <p>AI with Python (Coursera)</p>
                    <p>Internet of Things (NPTEL)</p>
                    <p>OpenCV & Image Processing (Infosys)</p>
                </ul>
              </p>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:sujigunasekar2005@gmail.com">sujigunasekar2005@gmail.com</a></p>
        <p>Phone: <a href="tel:+919577880887">9577880887</a></p>
        <p><strong>GitHub:</strong> <a href="https://github.com/sujigunasekar" target="_blank">GitHub Profile</a></p>
        <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/suji-g/" target="_blank">LinkedIn Profile</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Suji G. All rights reserved.</p>
    </footer>
</body>
</html>
```
### CSS
```
/* General Styling */
body {
  font-family: 'Helvetica Neue', Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f9f9f9;
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #1e1e2f;
  color: white;
  padding: 20px 0;
  text-align: center;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

header h1 {
  margin: 0;
  font-size: 2.5rem;
  letter-spacing: 1px;
  font-weight: 600;
}

nav ul {
  list-style-type: none;
  padding: 0;
  margin: 20px 0 0;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-size: 1rem;
  text-transform: uppercase;
  font-weight: 500;
}

nav ul li a:hover {
  color: #ff6600;
}

/* Section Styling */
section {
  padding: 60px 20px;
  margin: 0 auto;
  max-width: 1000px;
}

/* About Section */
#about {
  background-color: #ffffff;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  text-align: center;
}

#about .profile-pic {
  border-radius: 50%;
  width: 160px;
  height: 160px;
  object-fit: cover;
  margin-top: 20px;
}

#about h2 {
  font-size: 2rem;
  margin-bottom: 20px;
  font-weight: 600;
  color: #333;
}

#about p {
  font-size: 1.1rem;
  color: #555;
  margin: 20px 0;
}

#about a {
  color: #1e1e2f;
  font-weight: 600;
}

#about a:hover {
  color: #ff6600;
}

/* Education Section */
#education {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

#education p {
  font-size: 1.1rem;
  color: #555;
  margin: 10px 0;
}

/* Skills Section */
#skills {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

#skills p {
  font-size: 1.1rem;
  color: #555;
  margin: 10px 0;
}

/* Projects Section */
#projects {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.project {
  background-color: #f9f9f9;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 6px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
}

.project h3 {
  font-size: 1.6rem;
  color: #333;
  margin-bottom: 10px;
  font-weight: 600;
}

.project p {
  font-size: 1rem;
  color: #666;
}

/* Internships Section */
#internships {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.internship {
  background-color: #f9f9f9;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 6px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
}

.internship h3 {
  font-size: 1.6rem;
  color: #333;
  margin-bottom: 10px;
  font-weight: 600;
}

.internship p {
  font-size: 1rem;
  color: #666;
}

/* Achievements Section */
#achievements {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

#achievements p {
  font-size: 1.1rem;
  color: #555;
  margin: 10px 0;
}

#achievements ul {
  list-style-type: none;
  padding: 0;
}

#achievements ul p {
  margin: 10px 0;
  font-size: 1.1rem;
  color: #555;
}

/* Contact Section */
#contact {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

#contact p {
  font-size: 1.1rem;
  color: #555;
  margin: 10px 0;
}

#contact a {
  color: #ff6600;
  font-weight: 600;
}

#contact a:hover {
  color: #1e1e2f;
}

/* Footer */
footer {
  background-color: #1e1e2f;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
}

footer p {
  margin: 0;
  font-size: 1rem;
}

/* Responsive Design */
@media screen and (max-width: 768px) {
  header h1 {
      font-size: 2rem;
  }

  nav ul li {
      display: block;
      margin: 10px 0;
  }

  nav ul li a {
      font-size: 1rem;
  }

  section {
      padding: 40px 20px;
  }
}
```

## OUTPUT
![Screenshot 2025-03-26 093449](https://github.com/user-attachments/assets/5a962477-dddf-4f2c-9e7c-23ee3a4abe09)

![Screenshot 2025-03-26 093526](https://github.com/user-attachments/assets/efde8cbd-1799-46f9-82aa-a27a0184339d)

![Screenshot 2025-03-26 093542](https://github.com/user-attachments/assets/3dc4bd93-1869-40d5-8fbd-543f37218f59)

![Screenshot 2025-03-26 093625](https://github.com/user-attachments/assets/af21e0cd-d571-4d8d-b672-35f58d741bda)

![Screenshot 2025-03-26 093639](https://github.com/user-attachments/assets/57aedddb-3b27-41d6-99f7-f93fd6fcf6ff)

![Screenshot 2025-03-26 093647](https://github.com/user-attachments/assets/1f8b900c-32c9-4812-a2e0-76b52215204a)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
