 <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>YL - Software Company</title>
    <link rel="stylesheet" href="/test.css">
</head>

<body>
    <header>
        <nav>
            <div class="logo">
                <h1>Young <span> < </span> Lead </h1>
            </div>
            <ul class="nav-links">
                <li><a href="#home" id="Home1">Home</a></li>
                <li><a href="#about" id="about1">About Us</a></li>
                <li><a href="#services" id="services1">Services</a></li>
                <li><a href="#contact" id="contact1">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section  class="hero"><div id="hover">
        <div class="hero-content">
            <h1> <span> < </span> Innovative Software Solutions for Your Business</h1>
            <p>We deliver cutting-edge software solutions to help your business grow.</p><br>
            <a href="#contact" class="cta-button">Get in Touch</a>
        </div>
    </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Us</h2>
            <p>YounLead is a leading software development company specializing in custom solutions, mobile app development, and enterprise software. We focus on delivering high-quality products that exceed client expectations.</p>
        </div>
    </section>

    <section id="services" class="services">
        <div class="container">
            <h2>Our Services</h2> <h4>Improve Our Qualities For Your Expectations</h4>
            <div class="service-item">
                <h3>Custom Software Development</h3>
                <p>We build tailored software applications that cater to your business needs and goals.</p>
            </div>
            <div class="service-item">
                <h3>Mobile App Development</h3>
                <p>Our team creates responsive and intuitive mobile applications for Android and iOS.</p>
            </div>
            <div class="service-item">
                <h3>Enterprise Solutions</h3>
                <p>We design scalable, secure, and efficient enterprise software solutions to streamline operations. it helps to get to touch in your coustemer.They can get easily get your online website on their phone</p>
            </div>
            <div>
                <h3>Links</h3><span> Scan This</span> <br>
                   <img src="/images/WhatsApp Image 2024-11-15 at 10.32.14_4b2cf00d qr.jpg" width="150px" width="150px"><br>
                   WhatsApp :<span> 87781093XX</span> //  Gmail : <span>nathiyainfom@gmail.com</span>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us :</h2>
           <span> Gmail     : nathiyainfom@gmail.com<br>
                  Contact-No : 8778109XXX<br>
           </span>
            <h2>Any Ideas</h2>
            <form id="contact-form">
                <label for="name">Your Name</label>
                <input type="text" id="name" name="name" required placeholder="Enter your name">
                
                <label for="email">Your Email</label>
                <input type="email" id="email" name="email" required placeholder="Enter your email">

                <label for="message">Your Message</label>
                <textarea id="message" name="message" required placeholder="Write your message"></textarea>
                   <br>
                <button type="submit">Submit</button><br>
            </form>
            <p id="ceo">  <span> < </span> FOUNDER   /   CEO <br>
                NandhaKumar A</p>
        </div>
    </section><br>
   
    <footer>
        <p>&copy; 2024 YoungLead(YL). All rights reserved.</p>
    </footer>
    <script src="/test.js"></script>
</body>

</html>
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

/* Header (Navigation Bar) */
header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 2rem;
}

nav .logo h1 {
    font-size: 2rem;
}

nav .nav-links {
    list-style: none;
}

nav .nav-links li {
    display: inline;
    margin-left: 20px;
}

nav .nav-links a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1rem;
}

/* Hero Section */
.hero {
    background: url('/images/Backgrounds-Business-HD.jpg')  no-repeat center center/cover;
    color: #060606;
    text-align: center;
    padding: 100px 0;
}

.hero h1 {
    font-size: 3rem;
}

.hero p {
    font-size: 1.2rem;
    margin-top: 10px;
}

.cta-button {
    background: #f7a500;
    padding: 10px 20px;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px;
    font-size: 1.1rem;
}

/* About Section */
.about {
    padding: 50px 0;
    background: #f4f4f4;
    text-align: center;
}

.about h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.about p {
    font-size: 1.1rem;
    line-height: 1.6;
}

/* Services Section */
.services {
    padding: 50px 0;
}

.services .container {
    text-align: center;
}

.services h2 {
    font-size: 2.5rem;
    margin-bottom: 30px;
}

.service-item {
    margin: 30px 0;
}

.service-item h3 {
    font-size: 2rem;
    margin-bottom: 10px;
}

.service-item p {
    font-size: 1.1rem;
}

/* Contact Section */
.contact {
    padding: 50px 0;
    background: #f4f4f4;
}

.contact .container {
    text-align: center;
}

.contact h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

form {
    width: 50%;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
}

form input, form textarea {
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background: #f7a500;
    padding: 10px 20px;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

form button:hover {
    background: #f89c42;
}

/* Footer */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

span{
    color:#f7a500;
}

#ceo{
    letter-spacing: 2px;
    font-size: 1rem;
    font-weight: bold;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

#Home1{
    color:#f7a500;
}

#Home1:hover{
    color:white;
}

#about1{
    color:#f7a500;
}

#about1:hover{
    color:white;
}

#services1{
    color: #f7a500;
}

#services1:hover{
    color:white;
}

#contact1{
    color: #f7a500;
}

#contact1:hover{
    color:white;
}

// Simple form validation to ensure all fields are filled
document.getElementById('contact-form').addEventListener('submit', function (event) {
    event.preventDefault();

    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const message = document.getElementById('message').value;

    if (name === '' || email === '' || message === '') {
        alert('Please fill in all fields');
    } else {
        alert('Thank you for contacting us!');
        // Optionally, reset the form after submission
        document.getElementById('contact-form').reset();
    }
});

  
