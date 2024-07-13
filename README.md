# CLONE OF DRIBBLE WEBSITE

# AIM:
   To create a clone website with using Advance CSS.
   
# PROGRAM:
```

# home.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribble Clone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #24292e;
            padding: 10px 20px;
            color: #fff;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            font-size: 24px;
            margin: 0;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-left: 20px;
        }
        .hero {
            background-image: url('BG.jpg');
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #fff;
        }
        .hero h2 {
            font-size: 36px;
            margin: 0;
            padding: 10px;
        }
        .hero p {
            font-size: 18px;
            margin: 0;
            padding: 10px;
        }
        .button {
            display: inline-block;
            background-color: #3a02e0;
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 5px;
            margin-top: 20px;
            transition: background-color 0.3s ease;
        }
        .button:hover {
            background-color: #f7f9fa;
        }
        .featured-designs {
            padding: 20px;
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }
        .featured-design {
            background-color: #f0f0f0;
            padding: 10px;
            border-radius: 5px;
        }
        .featured-design img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dribble Clone</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="explore.html">Explore</a></li>
                <li><a href="signup.html">Sign Up</a></li>
                <li><a href="login.html">Log In</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h2>Discover the world's top designers & creatives.</h2>
        <p>Dribble is the leading destination to find & showcase creative work and home to the world's best design professionals.</p>
        <a href="#" class="button">Explore Designs</a>
    </section>
    <section class="featured-designs">
        <div class="featured-design">
            <img src="MM.jpg" alt="Featured Design 1">
            <h3>The Endless forest</h3>
            <p>by Mary Maka</p>
        </div>
        <div class="featured-design">
            <img src="MC.jpg" alt="Featured Design 2">
            <h3>Art Station</h3>
            <p>by Manuel Cetina</p>
        </div>
        <div class="featured-design">
            <img src="e9.png" alt="Featured Design 2">
            <h3>Valencia Design</h3>
            <p>by Lisa McCormick</p>
        </div>
        <div class="featured-design">
            <img src="e10.jpg" alt="Featured Design 2">
            <h3>Jetpack - Snowboard Design</h3>
            <p>by Jetpacks and Rollerskates</p>
        </div>
        <!-- Repeat for more featured designs -->
    </section>
    <footer>
        <p>&copy; 2024 Dribble Clone. All rights reserved.</p>
        <nav>
            <ul>
                <li><a href="#">About</a></li>
                <li><a href="#">Careers</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </footer>
</body>
</html>




# about.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - Dribble Clone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background-color: #24292e;
            padding: 10px 20px;
            color: #fff;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            font-size: 24px;
            margin: 0;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-left: 20px;
        }
        .content {
            padding: 20px;
        }
        .content h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }
        .content p {
            font-size: 18px;
            margin-bottom: 10px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dribble Clone</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="#">Explore</a></li>
                <li><a href="#">Sign Up</a></li>
                <li><a href="#">Log In</a></li>
            </ul>
        </nav>
    </header>
    <div class="content">
        <h2>About Us</h2>
        <p>Welcome to Dribble Clone, a simplified version inspired by the world's leading community for creatives to share, grow, and get hired.</p>
        <p>Our mission is to provide a platform where designers, artists, and creative professionals can showcase their work, connect with others, and explore innovative designs across various disciplines.</p>
        <p>Feel free to explore and get inspired by the diverse range of creative work showcased here!</p>
    </div>
    <footer>
        <p>&copy; 2024 Dribble Clone. All rights reserved.</p>
    </footer>
</body>
</html>


# explore.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Explore - Dribble Clone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background-color: #24292e;
            padding: 10px 20px;
            color: #fff;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            font-size: 24px;
            margin: 0;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-left: 20px;
        }
        .content {
            padding: 20px;
        }
        .content h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }
        .content p {
            font-size: 18px;
            margin-bottom: 10px;
        }
        .explore-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }
        .explore-item {
            background-color: #f0f0f0;
            padding: 10px;
            border-radius: 5px;
        }
        .explore-item img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dribble Clone</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="explore.html">Explore</a></li>
                <li><a href="#">Sign Up</a></li>
                <li><a href="#">Log In</a></li>
            </ul>
        </nav>
    </header>
    <div class="content">
        <h2>Explore Designs</h2>
        <p>Discover a wide range of creative designs from top designers around the world. Click on a design to view more details.</p>
        <div class="explore-grid">
            <div class="explore-item">
                <img src="e1.jpg" alt="Design 1">
                <h3>Widakk Design</h3>
                <p>by Srdjan Vidakovic</p>
            </div>
            <div class="explore-item">
                <img src="e2.png" alt="Design 2">
                <h3>Duolingo Design Streetwear</h3>
                <p>Dingbat Co.</p>
            </div>
            <div class="explore-item">
                <img src="e3.jpg" alt="Design 3">
                <h3>Rise Branding Design</h3>
                <p>by Sam Hox</p>
            </div>
            <div class="explore-item">
                <img src="e4.jpg" alt="Design 3">
                <h3>Blockchain: web design, landing page</h3>
                <p>by Daniel Sun for heartbeat</p>
            </div>
            <div class="explore-item">
                <img src="e5.png" alt="Design 3">
                <h3>Art Institute Blog Design</h3>
                <p>by tubik</p>
            </div>
            <div class="explore-item">
                <img src="e6.jpg" alt="Design 3">
                <h3>Coffee Package Design</h3>
                <p>by Shakuro Graphics</p>
            </div>
            <div class="explore-item">
                <img src="e7.jpg" alt="Design 3">
                <h3>Logo Design</h3>
                <p>by Kevin Kroneberger</p>
            </div>
            <div class="explore-item">
                <img src="e8.png" alt="Design 3">
                <h3>Gate Protocol / Web Design</h3>
                <p>by Mike | Creative Mints</p>
            </div>
            <!-- Repeat for more designs -->
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Dribble Clone. All rights reserved.</p>
    </footer>
</body>
</html>



# signup.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up - Dribbble Clone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background-color: #24292e;
            padding: 10px 20px;
            color: #fff;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            font-size: 24px;
            margin: 0;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-left: 20px;
        }
        .content {
            padding: 20px;
        }
        .content h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }
        .content form {
            max-width: 500px;
            margin: auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            background-color: #f9f9f9;
        }
        .content form label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }
        .content form input[type="text"],
        .content form input[type="email"],
        .content form input[type="password"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .content form input[type="submit"] {
            background-color: #1e88e5;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        .content form input[type="submit"]:hover {
            background-color: #1565c0;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dribbble Clone</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="explore.html">Explore</a></li>
                <li><a href="signup.html">Sign Up</a></li>
                <li><a href="#">Log In</a></li>
            </ul>
        </nav>
    </header>
    <div class="content">
        <h2>Create an Account</h2>
        <form action="#" method="post">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>

            <input type="submit" value="Sign Up">
        </form>
    </div>
    <footer>
        <p>&copy; 2024 Dribble Clone. All rights reserved.</p>
    </footer>
</body>
</html>



# login.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Log In - Dribble Clone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background-color: #24292e;
            padding: 10px 20px;
            color: #fff;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            font-size: 24px;
            margin: 0;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-left: 20px;
        }
        .content {
            padding: 20px;
        }
        .content h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }
        .content form {
            max-width: 500px;
            margin: auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            background-color: #f9f9f9;
        }
        .content form label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }
        .content form input[type="text"],
        .content form input[type="email"],
        .content form input[type="password"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .content form input[type="submit"] {
            background-color: #1e88e5;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        .content form input[type="submit"]:hover {
            background-color: #1565c0;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dribble Clone</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="explore.html">Explore</a></li>
                <li><a href="signup.html">Sign Up</a></li>
                <li><a href="login.html">Log In</a></li>
            </ul>
        </nav>
    </header>
    <div class="content">
        <h2>Log In to Your Account</h2>
        <form action="#" method="post">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>

            <input type="submit" value="Log In">
        </form>
    </div>
    <footer>
        <p>&copy; 2024 Dribble Clone. All rights reserved.</p>
    </footer>
</body>
</html>
```

# output
![1st page](https://github.com/bharathipriyan08/CSS-ADAVANCE-PROJECT/assets/113762012/645cd302-8f8c-4157-92a3-436a6c80e2e6)

![Screenshot (6)](https://github.com/bharathipriyan08/CSS-ADAVANCE-PROJECT/assets/113762012/79c40554-b6f9-441f-9ec1-67fb12f93914)

![Screenshot (5)](https://github.com/bharathipriyan08/CSS-ADAVANCE-PROJECT/assets/113762012/fe98902e-2d89-4d74-a232-9af34bc5ea07)

![Screenshot (7)](https://github.com/bharathipriyan08/CSS-ADAVANCE-PROJECT/assets/113762012/91745633-7c98-45b9-965f-c31e865c6faf)

![Screenshot (8)](https://github.com/bharathipriyan08/CSS-ADAVANCE-PROJECT/assets/113762012/e16d6321-e5d5-4da9-be8a-2ac988a30dde)
