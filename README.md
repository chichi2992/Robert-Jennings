# Robert-Jennings
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Discover the Turks and Caicos Islands">
    <title>Discover Turks and Caicos</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" />
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/lightgallery@2.4.0/css/lightgallery.min.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#destinations">Destinations</a></li>
                <li><a href="#activities">Activities</a></li>
                <li><a href="#map">Map</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Discover the Turks and Caicos Islands</h1>
        <p>Plan your perfect getaway</p>
    </section>

    <section id="map">
        <h2>Interactive Map</h2>
        <div id="interactive-map" style="height: 400px;"></div>
    </section>

    <section id="gallery">
        <h2>Island Gallery</h2>
        <div id="lightgallery">
            <a href="gallery/photo1.jpg"><img src="gallery/thumb1.jpg" alt="Image 1"></a>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Turks and Caicos. All rights reserved.</p>
    </footer>

    <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/lightgallery@2.4.0/lightgallery.umd.js"></script>
    <script src="script.js"></script>
</body>
</html>

