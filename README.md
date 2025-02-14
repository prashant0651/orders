<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Neonbyte Web Hosting Company Ltd.</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
    <style>
        body {
            background-color: #0a0a0a;
            color: #00d4ff;
            font-family: 'Arial', sans-serif;
            text-align: center;
        }
        header {
            background: linear-gradient(90deg, #000428, #004e92);
            padding: 20px;
            border-bottom: 3px solid #00d4ff;
            box-shadow: 0 0 15px #00d4ff;
        }
        .logo, .profile-pic {
            width: 100px;
            border-radius: 50%;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #00d4ff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #ffffff;
        }
        section {
            margin: 40px 0;
            padding: 20px;
            background: rgba(0, 0, 0, 0.7);
            border: 2px solid #00d4ff;
            box-shadow: 0 0 10px #00d4ff;
            border-radius: 10px;
            display: inline-block;
            width: 80%;
        }
        button {
            background: #00d4ff;
            border: none;
            padding: 10px 20px;
            color: #000;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s;
            border-radius: 5px;
        }
        button:hover {
            background: #ffffff;
            color: #000;
        }
    </style>
</head>
<body>
    <header>
        <img src="Screenshot 2025-02-14 050038.png" alt="Neonbyte Logo" class="logo">
        <h1>Neonbyte Web Hosting Company Ltd.</h1>
        <img src="IMG_20241222_204244.jpg" alt="Prashant Kumar Singh" class="profile-pic">
        <p>Director & Co-founder: Prashant Kumar Singh</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#web-development">Web Development</a></li>
            <li><a href="#web-hosting">Web Hosting</a></li>
            <li><a href="#thumbnails">Thumbnails</a></li>
            <li><a href="#logos">Logos</a></li>
            <li><a href="#custom-order">Custom Order</a></li>
            <li><a href="#govt-services">Govt. Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="web-development">
        <h2>Web Development</h2>
        <button onclick="placeOrder('Web Development')">Order Now</button>
    </section>
    
    <section id="web-hosting">
        <h2>Web Hosting</h2>
        <button onclick="placeOrder('Web Hosting')">Order Now</button>
    </section>
    
    <section id="thumbnails">
        <h2>Thumbnails</h2>
        <button onclick="placeOrder('Thumbnails')">Order Now</button>
    </section>
    
    <section id="logos">
        <h2>Logos</h2>
        <button onclick="placeOrder('Logos')">Order Now</button>
    </section>
    
    <section id="custom-order">
        <h2>Custom Order</h2>
        <form id="customOrderForm">
            <textarea placeholder="Describe your custom idea..."></textarea>
            <button type="submit">Submit</button>
        </form>
    </section>
    
    <section id="govt-services">
        <h2>Government Services</h2>
        <p>All types of government services are available, including:</p>
        <ul>
            <li>Passport</li>
            <li>Visa</li>
            <li>Aadhar</li>
            <li>PAN</li>
            <li>Driving License</li>
            <li>Birth & Death Certificates</li>
            <li>Caste Certificate</li>
            <li>Income Certificate</li>
            <li>Residence Certificate</li>
            <li>EWS Certificate</li>
            <li>OBC-NCL Certificate</li>
            <li>Ration Card</li>
            <li>Marriage Certificate</li>
            <li>Property Registration</li>
            <li>Police Clearance Certificate</li>
            <li>Any other government documentation services</li>
        </ul>
        <button onclick="placeOrder('Government Services')">Apply Now</button>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Phone: +91 7067185187</p>
        <p>Email: <a href="mailto:prashantkumarsingh065@gmail.com">prashantkumarsingh065@gmail.com</a></p>
        <p><a href="https://www.instagram.com/o_o.prashantkumarsingh.o_o?igsh=em9tN3dlMGhwcDJ1" target="_blank">Instagram Profile</a></p>
        <p><a href="https://facebook.com/share/15d7hCXisD/" target="_blank">Facebook Profile</a></p>
    </section>
    
    <script src="script.js"></script>
</body>
</html>
