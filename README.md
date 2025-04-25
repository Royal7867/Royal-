<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apki Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Apki Website Mein Swagat Hai!</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Home</h2>
        <p>Ye aapki website ka homepage hai. Yahan aap apna content add kar sakte hain.</p>
    </section>

    <section id="about">
        <h2>About</h2>
        <p>Apne baare mein yahan likhein. Ye section aapki story ya services ke liye hai.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: aapka-email@example.com</p>
        <p>Phone: +91 1234567890</p>
    </section>

    <footer>
        <p>&copy; 2025 Apki Website. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>styles.cssbody {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 2rem;
    margin: 1rem;
    background: #f4f4f4;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 1rem;
    background: #333;
    color: #fff;
}

h1, h2 {
    color: #333;
}
