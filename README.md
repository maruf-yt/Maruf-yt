<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Watch Movie Now</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #111;
            color: white;
        }
        .container {
            margin-top: 50px;
        }
        .movie-banner, .certificate {
            width: 100%;
            max-width: 600px;
            border-radius: 10px;
            display: block;
            margin: 0 auto;
        }
        .gif {
            width: 300px; /* GIF বড় করা হয়েছে */
            margin-top: 20px;
        }
        .watch-button {
            display: inline-block;
            margin-top: 20px;
            padding: 15px 30px;
            font-size: 20px;
            color: white;
            background-color: red;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            cursor: pointer;
        }
        .watch-button:hover {
            background-color: darkred;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🔥 Watch the Most Popular Movie Now 🔥</h1>
        
        <!-- সেন্সর সার্টিফিকেট ইমেজ -->
        <img src="certificate_image.jpg" alt="Censor Certificate" class="certificate">
        
        <!-- মুভি ব্যানার -->
        <img src="https://m.media-amazon.com/images/I/71Bok3N3OXL._AC_UF1000,1000_QL80_.jpg" alt="Movie Banner" class="movie-banner">
        
        <p>Click below to watch the full movie.</p>

        <!-- GIF -->
        <img src="https://media.giphy.com/media/jAYUbVXgESSti/giphy.gif" alt="GIF Animation" class="gif">
        
        <br>
        
        <!-- Watch Now Button -->
        <a href="https://your-affiliate-link.com" class="watch-button">🎬 Watch Now</a>
    </div>
</body>
</html>
