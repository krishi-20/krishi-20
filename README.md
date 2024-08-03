<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Design Template</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        .header, .footer {
            background-color: #f1f1f1;
            padding: 20px;
            text-align: center;
        }
        .header .nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .header .nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #333;
        }
        .hero {
            padding-left: 500px;
            padding: 20px 100px;
            background-color: #e9e9e9;
        
        }
        .section {
            padding: 20px;
            text-align: center;
        }
        .features {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .features .feature {
            flex: 1 1 calc(33% - 40px);
            margin: 20px;
            padding: 20px;
            background-color: #f9f9f9;
        }
        .cta {
            display: inline-block;
            margin: 20px 0;
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            text-decoration: none;
            
        

        }
        .footer {
            background-color: #333;
            color: white;
            padding: 40px 20px;
            text-align: left;
        }
        .footer .content {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .footer .content div {
            flex: 1 1 calc(33% - 40px);
            margin: 20px;
        }
        .footer .content div ul {
            list-style: none;
            padding: 0;
        }
        .footer .content div ul li {
            margin: 10px 0;
        }
        .footer .content div ul li a {
            color: white;
            text-decoration: none;
        }
        .footer .bottom {
            text-align: center;
            margin-top: 20px;
            border-top: 1px solid #555;
            padding-top: 20px;
        }
    </style>
</head>
<body>

    <div class="header">
        <div class="nav">
            <div class="logo">Logo</div>
            <div class="menu">
                <a href="#">Home</a>
                <a href="#">About Us</a>
                <a href="#">Contact</a>
            </div >
            <a href="#" class="cta">Call to action</a>
        </div>
    </div>

    <div class="hero">
        <h1 style="padding-right:800px;">The future of web <br>design, today</h1>
        <p style="padding-right:850px;" >The future of web design, today</p>
        <a  href="#" style="padding-right:900px;" class="cta">Call to action</a>
        
    </div>

    <div class="section" style="background: grey;">
        <h1 style="padding-right:600px;">Don't forget to grab this one, it's free!</h1>
        <p style="padding-right:900px;">Download the Ultimate con tomate guide.</p>
        <a   href="#" class="cta">Call to action</a>
    </div>

    <div class="section">
        <h2>What we do</h2>
        <p>Our mission is very important to the planet: we plant as many trees as possible.</p>
        <p>Can you figure out?</p>
        <ul>
            <li>We recycle everything we see</li>
            <li>We teach people how to reuse their stuff</li>
            <li>We believe in human beings as problem solvers</li>
        </ul>
    </div>

    <div class="section features">
        <div class="feature">
            <h3>The future of web design, today</h3>
            <p>The future of web design, today</p>
            <a href="#" class="cta">Call to action</a>
        </div>
        <div class="feature">
            <h3>The future of web design, today</h3>
            <p>The future of web design, today</p>
            <a href="#" class="cta">Call to action</a>
        </div>
        <div class="feature">
            <h3>The future of web design, today</h3>
            <p>The future of web design, today</p>
            <a href="#" class="cta">Call to action</a>
        </div>
    </div>

    <div class="section">
        <p>Our mission is very important to the planet: we plant as many trees as possible. Can you figure out?</p>
        <a href="#" class="cta">Call to action</a>
    </div>

    <div class="footer">
        <div class="content">
            <div>
                <h3>More Information</h3>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About us</a></li>
                    <li><a href="#">Shop</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </div>
            <div>
                <h3>Stay in Contact</h3>
                <ul>
                    <li><a href="mailto:info@contact.com">info@contact.com</a></li>
                    <li><a href="tel:+34654654654">+34 654 654 654</a></li>
                </ul>
            </div>
            <div>
                <h3>Subscribe now to the newsletter</h3>
                <form>
                    <input type="text" name="name" placeholder="Your name"><br>
                    <input type="email" name="email" placeholder="Your email"><br>
                    <input type="checkbox" name="privacy"> I consent the privacy policy<br>
                    <button type="submit">Subscribe</button>
                </form>
            </div>
        </div>
        <div class="bottom">
            <p>Basic Components © 2022. All rights reserved.</p>
            <p>
                <a href="#">Privacy Policy</a> |
                <a href="#">Cookies</a> |
                <a href="#">Legal Advice</a> |
                <a href="#">FAQ</a>
            </p>
            <p>Made by Author</p>
        </div>
    </div>

</body>
</html>
