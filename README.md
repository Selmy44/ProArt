# ProArt
ProArt2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Art Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        h1 {
            margin: 0;
        }

        nav {
            background-color: #444;
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
            margin: 0 10px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .art-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin: 20px;
        }

        .art-piece {
            background-color: #fff;
            border: 1px solid #ddd;
            box-shadow: 2px 2px 5px #888;
            margin: 10px;
            padding: 10px;
            width: 250px;
            text-align: center;
        }

        .art-title {
            font-weight: bold;
        }

        .art-description {
            margin-top: 10px;
        }

        .art-image {
            max-width: 100%;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to the Art Gallery</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Artists</a>
        <a href="#">Exhibitions</a>
        <a href="#">Contact</a>
    </nav>

    <div class="art-container">
        <div class="art-piece">
            <img class="art-image" src="artwork1.jpg" alt="Artwork 1">
            <div class="art-title">Artwork 1</div>
            <div class="art-description">A beautiful painting with vibrant colors.</div>
        </div>

        <div class="art-piece">
            <img class="art-image" src="artwork2.jpg" alt="Artwork 2">
            <div class="art-title">Artwork 2</div>
            <div class="art-description">A stunning sculpture made from marble.</div>
        </div>

        <!-- Add more art pieces as needed -->
    </div>

    <footer>
        &copy; 2023 Art Gallery. All rights reserved.
    </footer>

    <script>
        // You can add JavaScript code here for interactivity or dynamic content.
    </script>
</body>
</html>
