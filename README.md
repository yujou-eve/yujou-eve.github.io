<html>
<head>
  <title>Yujou - Personal Website</title>
  <link rel="stylesheet" href="styles.css"> <!-- Import the CSS stylesheet -->/* General Styles */
body {
  font-family: "Georgia", "Times New Roman", serif; /* Classic serif font */
  color: #333; /* Dark gray text color */
  background-color: #f0f0f0; /* Light gray background color */
}

/* Navigation Menu */
nav {
  background-color: #333; /* Dark gray menu background color */
  padding: 10px; /* Menu inner padding */
}

ul {
  list-style: none; /* Remove list item bullets */
  margin: 0;
  padding: 0;
}

li {
  display: inline-block; /* Horizontal arrangement of menu items */
  margin-right: 20px; /* Menu item spacing */
}

a {
  color: #ccc; /* Light gray menu link color */
  text-decoration: none; /* Remove link underline */
  padding: 5px 10px; /* Menu item inner padding */
}

a:hover {
  color: #fff; /* White link color on hover */
  background-color: #666; /* Medium gray background on hover */
}

/* Home, Profile, and CNRS Sections */
section {
  padding: 20px; /* Add padding around each section for spacing */
  margin-bottom: 30px; /* Add margin between sections for spacing */
  background-color: #fff; /* White background for sections */
  border: 1px solid #ccc; /* Add a light gray border to sections */
  border-radius: 5px; /* Add rounded corners to sections */
}

h2 {
  color: #333; /* Dark gray heading color */
}

img {
  max-width: 100%; /* Ensure the profile image fits within its container */
}

p {
  line-height: 1.6; /* Set a comfortable line-height for paragraphs */
}

</head>
<body>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#profile">Profile</a></li>
      <li><a href="#cnrs">CNRS</a></li>
    </ul>
  </nav>


 <!-- Home Section -->
  <section id="home">
    <h2>Bienvenue sur mon site Web personnel</h2>
    <p>Je m'appelle YuJou, Ting. Je suis étudiante en langues et littératures à l'Université de Tunghai, à Taiwan.</p>
  </section>

  <!-- Profile Section -->
  <section id="profile">
    <h2>Profile</h2>
    <img src="your-profile-image.jpg" alt="Your Profile Picture">
    <p>
     Je suis stagiaire au CNRS (Centre National de la recherche scientifique), travaillant sur le projet EVOGRAM.
    </p>
    <p>
      I graduated from Université TungHai with a degree in Language and Literatures. 
    </p>
  </section>

  <!-- CNRS Section -->
  <section id="cnrs">
    <h2>CNRS</h2>
    <p>
       CNRS (Centre national de la recherche scientifique).
    </p>
  </section>

  <!-- Add more sections or content as needed -->

</body>
</html>
