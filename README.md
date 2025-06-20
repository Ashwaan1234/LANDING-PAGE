<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="container">
            <h1 class="logo">MyLanding</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Features</a></li>
                    <li><a href="#">Pricing</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h2>Welcome to My Landing Page</h2>
            <p>Build amazing websites with clean design and efficient code.</p>
            <a href="#" class="btn">Get Started</a>
        </div>
    </section>

    <section class="features">
        <div class="container">
            <div class="feature-box">
                <h3>Responsive</h3>
                <p>Looks great on all devices.</p>
            </div>
            <div class="feature-box">
                <h3>Customizable</h3>
                <p>Easy to modify and expand.</p>
            </div>
            <div class="feature-box">
                <h3>User Friendly</h3>
                <p>Simple, intuitive interface.</p>
            </div>
        </div>
    </section>

    <section class="cta">
        <div class="container">
            <h2>Start Your Project Today</h2>
            <p>Join us to build your professional landing page now!</p>
            <a href="#" class="btn">Join Now</a>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 MyLanding. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
}

.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
    overflow: hidden;
}

header {
    background: #004aad;
    color: #fff;
    padding: 1rem 0;
}

header .logo {
    float: left;
    font-size: 24px;
    font-weight: bold;
    margin-left: 10px;
}

header nav {
    float: right;
    margin-right: 10px;
}

header ul {
    list-style: none;
}

header ul li {
    display: inline;
    margin: 0 10px;
}

header ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background: #e3e8f0;
    padding: 60px 0;
    text-align: center;
}

.hero h2 {
    font-size: 36px;
    margin-bottom: 10px;
}

.hero p {
    font-size: 18px;
    margin-bottom: 20px;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    background: #004aad;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

.features {
    display: flex;
    justify-content: space-between;
    padding: 40px 0;
    background: #fff;
}

.feature-box {
    flex: 1;
    padding: 20px;
    margin: 0 10px;
    background: #f0f8ff;
    border-radius: 10px;
    text-align: center;
}

.cta {
    background: #004aad;
    color: #fff;
    text-align: center;
    padding: 40px 0;
}

footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}
landing-page/
├── index.html
├── style.css
