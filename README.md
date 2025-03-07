# Dynamic HR Solutions
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Dynamic HR Solutions</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>This is a simple website created to demonstrate basic HTML, CSS, and JavaScript.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Web Development</li>
            <li>Graphic Design</li>
            <li>SEO Optimization</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 My Simple Website</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    line-height: 1.6;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin-bottom: 10px;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: #fff;
    border-radius: 8px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: #fff;
    position: fixed;
    bottom: 0;
    width: 100%;
}

footer p {
    margin: 0;
}

// Example: Alert when the page is loaded
window.onload = function() {
    alert("Welcome to My Simple Website!");
};
