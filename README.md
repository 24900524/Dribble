# Project Responsive Web Design using Bootstrap
## Date: 26.12.2024

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
pharm.html
<html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body class="text-center">
        <nav class="navbar navbar-expand-lg navbar-light bg-success">
            <div class="container-fluid">
                <a class="navbar-brand text-dark" href="C:\Users\Sashmitha sree\Documents\SEM 1\web app\Practise code\homeweb.html">DHARSHINI PHARMACY</a>
                
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav d-flex">
                        <li class="nav-item " >
                            <a class="nav-link text-white" href=" C:\Users\Sashmitha sree\Documents\SEM 1\web app\Practise code\pharm.html">HOME</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link text-white" href="C:\Users\Sashmitha sree\Documents\SEM 1\web app\Practise code\product.html">PRODUCTS</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" href="C:\Users\Sashmitha sree\Documents\SEM 1\web app\Practise code\about.html">ABOUT</a>
                        </li>
                    </ul>
                </div>
                
            </div>
        </nav>
        <div class="row">
            <div class="col">
                <br><br>
                <h1>Welcome to Our Pharmacy</h1>
                <p>We provide a variety of pharmaceutical products and services. Your health is our priority!</p>
            </div>
        </div>
        <img  src="logo1.jpg">
        <footer class="bg-light text-center py-3">
            <p>Designed and Developed by DHARSHINI S N</p>
        </footer>
    </body>

    </html>

product.html
<html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-warning">
            <div class="container-fluid">
                <a class="navbar-brand text-dark" href="#">PHARMACY COMPANY</a>
                
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav d-flex">
                        <li class="nav-item " >
                            <a class="nav-link text-white" href="C:\Users\admin\home.html">HOME</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link text-white" href="C:\Users\admin\product.html">PRODUCTS</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" href="C:\Users\admin\about.html">ABOUT</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
       
        <div class="row">
            <div class="col-12">
                <h2>Contact Us</h2>
                <form>
                    <div class="form-group">
                        <label for="name">Your Name</label>
                        <input type="text" class="form-control" id="name" placeholder="Enter your name">
                    </div>
                    <div class="form-group">
                        <label for="email">Email address</label>
                        <input type="email" class="form-control" id="email" placeholder="Enter email">
                    </div>
                    <div class="form-group">
                        <label for="message">Message</label>
                        <textarea class="form-control" id="message" rows="3" placeholder="Your message"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Submit</button>
                </form>
            </div>
        </div>
    </div>
    <footer class="bg-light text-center py-3">
        <p>Designed and Developed by DHARSHINI S N</p>
    </footer>
    </body>

</html>

main.html
<html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body class="text-center">
        <nav class="navbar navbar-expand-lg navbar-light bg-warning">
            <div class="container-fluid">
                <a class="navbar-brand text-dark" href="#">PHARMACY COMPANY</a>
                
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav d-flex">
                        <li class="nav-item " >
                            <a class="nav-link text-white" href="C:\Users\admin\home.html">HOME</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link text-white" href="C:\Users\admin\product.html">PRODUCTS</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" href="C:\Users\admin\about.html">ABOUT</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <h1>DHARSHINI PHARMACY</h1>
        <img src="logo1.jpg">

<footer class="bg-light text-center py-3">
<p>Designed and Developed by DHARSHINI S N</p>
</footer>




</body>
</html>

about.html
<html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-success">
            <div class="container-fluid">
                <a class="navbar-brand text-dark" href="C:\Users\Sashmitha sree\Documents\SEM 1\web app\Practise code\homeweb.html">PHARMACY COMPANY</a>
                
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav d-flex">
                        <li class="nav-item " >
                            <a class="nav-link text-white" href=" C:\Users\Sashmitha sree\Documents\SEM 1\web app\Practise code\pharhome.html">HOME</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link text-white" href="C:\Users\Sashmitha sree\Documents\SEM 1\web app\Practise code\boot2.html">PRODUCTS</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" href="C:\Users\Sashmitha sree\Documents\SEM 1\web app\Practise code\about.html">ABOUT</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
           
                <p class="Toggle text">
                    About Us<br>

Welcome to Dharshini Pharmacy, your trusted partner in health and wellness. Established in 2020, we are dedicated to providing high-quality pharmaceutical care, personalized service, and expert guidance to ensure the well-being of our customers.
           
<br><br><br>
Who We Are<br>
At Dharshini pharmacy, we are more than just a pharmacy. We are a team of experienced healthcare professionals committed to improving the quality of life for our community. Our staff includes licensed pharmacists, knowledgeable technicians, and friendly support staff who are passionate about meeting your healthcare needs.
<br><br><br>
Our Mission<br>
Our mission is to deliver reliable, affordable, and accessible healthcare solutions tailored to each customer. We believe in fostering trust and building long-term relationships with our clients by consistently exceeding their expectations.
<br><br><br>
What We Offer<br>
Prescription Services: Fast and accurate prescription filling with expert advice.
Over-the-Counter Products: A wide range of health and wellness products, including vitamins, supplements, and personal care items.
Consultation Services: One-on-one consultations for medication management, health screenings, and wellness advice.
Home Delivery: Convenient and timely delivery of your medications right to your doorstep.
Specialty Medications: Support for complex conditions with specialized medications and care programs.
<br><br><br>Why Choose Us?<br>
Customer-Centric Care: Your health and satisfaction are our top priorities.
Expert Guidance: Our pharmacists provide personalized advice to help you make informed healthcare decisions.
Quality Assurance: We adhere to the highest standards of safety and quality in everything we do.
Community Commitment: We are proud to be an integral part of our community, supporting local initiatives and wellness programs.
<br><br><br>Our Vision<br>
We envision a healthier future where everyone has access to exceptional pharmaceutical care. By embracing innovation and staying at the forefront of the healthcare industry, we aim to be your lifelong partner in health.
<br><br><br>
Thank you for choosing Dharshini Pharmacy. We look forward to serving you and making a positive impact on your health journey.
                </p>
            </div>
        </nav>
        <footer class="bg-light text-center py-3">
            <p>Designed and Developed by DHARSHINI S N</p>
        </footer>
    </body>

</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-26 143528.png>)
![alt text](<Screenshot 2024-12-26 143615.png>)
![alt text](<Screenshot 2024-12-26 143623.png>)
![alt text](<Screenshot 2024-12-26 143646.png>)
![alt text](<Screenshot 2024-12-26 143707.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
