<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ferrari 488</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Ferrari 488</h1>
        <nav>
            <ul>
                <li><a href="#overview">Overview</a></li>
                <li><a href="#specs">Specifications</a></li>
                <li><a href="#gallery">Gallery</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="overview">
        <h2>Overview</h2>
        <p>The Ferrari 488 is a mid-engine sports car produced by the Italian automobile manufacturer Ferrari.</p>
        <!-- More detailed overview content goes here -->
    </section>
    
    <section id="specs">
        <h2>Specifications</h2>
        <ul>
            <li>Engine: 3.9 L twin-turbocharged V8</li>
            <li>Horsepower: 661 hp</li>
            <li>Top Speed: 205 mph</li>
            <!-- Add more specifications -->
        </ul>
    </section>
    
    <section id="gallery">
        <h2>Gallery</h2>
        <img src="/thumbs/2018/ferrari_488_pista_spider_4k-t2.jpg" alt="Ferrari 488 Pista Spider 4K" title="Ferrari 488 Pista Spider 4K" width="520" height="325">
    </section>

    <footer>
        <p>&copy; 2024 Ferrari. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #F00; /* Ferrari red */
    color: #FFF;
    padding: 20px;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #FFF;
    text-decoration: none;
}

section {
    padding: 20px;
}

footer {
    background-color: #F00; /* Ferrari red */
    color: #FFF;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
