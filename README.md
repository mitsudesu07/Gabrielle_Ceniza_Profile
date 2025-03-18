<!DOCTYPE html>
<html>
<meta charset="utf-8">
<link rel="stylesheet" href="style.css">

<body>

<div class="header">
<img src="profile-pic">
<h1>Welcome, I'm </h1>
</div>

<div class="body">
<h2>Relevant Coursework & Projects </h2>

<div class="projects">
<h3>USJ-R Website Redesign | June-July 2024</h3>
<li>Transforming the school website to provide a more user-friendly, visually engaging, and informative experience</li>
<li>The redesign utilizes HTML, CSS and JavaScript to create a modern layout, improved navigation, and enhanced accessibility.
</li>
</div>
<div class="projects">
<h3>Horizon 2-Day Hackathon | </h3>
<li>Participated in a 2-day hackathon focused on designing the user interface for a mobile application that helps users locate nearby electric car charging stations</li>
<li>Collaborated with a team to create an intuitive, responsive, and user-friendly interface</li>
<li>Utilized Figma for prototyping and Dart as the programming language, contributing to a seamless and efficient development process.
</li>  
</div>

<div class="projects">
<h3>Student Masterlist Project |</h3>
           <li> Developed a student management system as a final project using PHP, where users can securely sign up, log in, and manage a student masterlist. </li>
<li>The application allows users to add, update, and delete student records, providing an intuitive interface for seamless data management.</li>
</div>
</div>


</body>

<style>
           /* Global Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  background-color: #f4f4f4;
  line-height: 1.6;
}

h1, h2, h3 {
  color: #333;
}

h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}

h3 {
  font-size: 1.5rem;
  color: #444;
}

/* Header Styles */
.header {
  background-color: #2c3e50;
  color: white;
  text-align: center;
  padding: 40px 0;
}

.header img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  margin-bottom: 15px;
}

/* Body Styles */
.body {
  padding: 20px;
  max-width: 1000px;
  margin: 0 auto;
  background-color: white;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
}

.projects {
  margin-bottom: 25px;
}

.projects ul {
  list-style-type: none;
  padding-left: 20px;
}

.projects li {
  margin-bottom: 8px;
  line-height: 1.5;
}

.projects h3 {
  margin-bottom: 10px;
}

/* Styling for links */
a {
  color: #3498db;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* Responsiveness */
@media (max-width: 768px) {
  .header {
    padding: 20px 0;
  }

  .header img {
    width: 120px;
    height: 120px;
  }

  .body {
    padding: 15px;
  }
}

</style>

</html>
