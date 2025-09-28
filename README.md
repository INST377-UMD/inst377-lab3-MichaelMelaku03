[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/LXHgsJqg)
# INST377-Lab

# Name (Please Input your name): Michael Melaku

# Comments: index.html <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Rock Paper Scissors</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header -->
  <div class="header-footer">
    <h1>Rock Paper Scissors Game</h1>
  </div>

  <!-- Navigation -->
  <nav>
    <ul>
      <li><a href="https://www.google.com" target="_blank">Google</a></li>
      <li><a href="https://www.wikipedia.org" target="_blank">Wikipedia</a></li>
      <li><a href="https://www.youtube.com" target="_blank">YouTube</a></li>
    </ul>
  </nav>

  <!-- Body -->
  <div class="container">
    <!-- Main Content -->
    <div class="main-content">
      <h2>Play Now</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br><br>

        <label for="choice">Choose:</label>
        <select id="choice" name="choice">
          <option value="rock">Rock</option>
          <option value="paper">Paper</option>
          <option value="scissors">Scissors</option>
        </select><br><br>

        <button type="submit">Play</button>
      </form>
    </div>

    <!-- Sidebar -->
    <div class="sidebar">
      <h2>Rules</h2>
      <p>Rock beats Scissors</p>
      <p>Scissors beats Paper</p>
      <p>Paper beats Rock</p>
    </div>
  </div>

  <!-- Footer -->
  <div class="header-footer">
    <p>&copy; 2025 Rock Paper Scissors Game</p>
  </div>
</body>

styles.css  
body {
  font-family: Arial, sans-serif; 
  margin: 0;
  padding: 0;
}

/* Header + Footer */
.header-footer {
  background-color: #333;
  color: white;
  text-align: center; /* Centered text */
  padding: 20px;
  margin: 10px 0;
}

/* Navigation */
nav ul {
  list-style-type: none; /* Remove bullet points */
  margin: 0;
  padding: 0;
  display: flex; /* Horizontal layout */
  justify-content: center;
  background-color: #444;
}

nav li {
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  padding: 10px;
}

nav a:hover {
  background-color: #666; /* Hover state */
  border-radius: 5px;
}

/* Body Layout */
.container {
  display: flex; /* Put sidebar and main-content on same line */
  margin: 20px;
}

/* Main Content */
.main-content {
  width: 70%; /* Percentage width */
  margin: 10px;
  padding: 20px;
  background-color: #f9f9f9;
}

/* Sidebar */
.sidebar {
  width: 30%; /* Percentage width */
  margin: 10px;
  padding: 20px;
  background-color: #e3e3e3; /* Different color */
  transition: background-color 0.3s ease;
}

.sidebar:hover {
  background-color: #d1d1d1; /* Hover background change */
}

/* Form Input Behavior */
input[type="text"] {
  transition: width 0.3s ease;
  width: 200px;
}

input[type="text"]:focus {
  width: 300px; /* Expand on focus */
}
</html>

