# Elpolloloco
Just a test site 
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Apple-like Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Features</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">Support</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Welcome to My Modern Website</h1>
        <p>Experience sleek design and modern features.</p>
        <a href="#">Learn More</a>
    </section>

    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>
    
    <script src="script.js"></script>
</body>
</html>
styles.css
/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    color: #333;
    text-align: center;
}

/* Header & Navigation */
header {
    background-color: #000;
    padding: 20px;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 16px;
}

/* Hero Section */
.hero {
    background-color: #111;
    color: white;
    padding: 100px 20px;
}

.hero h1 {
    font-size: 50px;
}

.hero p {
    font-size: 20px;
    margin: 20px 0;
}

.hero a {
    padding: 10px 20px;
    background-color: #ff6600;
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.hero a:hover {
    background-color: #cc5200;
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    padding: 10px;
}
script.js 
// script.js
console.log("Website Loaded!");
