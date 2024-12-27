# Project Responsive Web Design using Bootstrap
## Date:23.12.2024

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
'''
about.html
<html>
    <head>
        <title>
            About
        </title>
        <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
        <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
        <style>
            .navbar 
            {
                background-color: rgb(47, 8, 188); 
            }
            footer {
                position: fixed;
                bottom: 0;
                width: 100%;
                background-color: rgb(91, 241, 26);
                color: rgb(8, 8, 8);
                padding: 10px 0;
            }
            .col {
                border: 1px solid #ddd;
                border-radius: 5px;
                padding: 10px;
                text-align: center;
                flex: 1 1 calc(25% - 40px);
                box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            }
        </style>
    </head>
    <body>

<nav class="navbar navbar-expand-lg navbar-dark bg-plum">
            <a class="navbar-brand" href="#">Pharmacy</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
        
<div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav mr-auto">
                <li class="nav-item">
                  <a class="nav-link" href="ph.html">Home</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="about.html">About us</a>
                </li>
                <li class="nav-item active">
                  <a class="nav-link" href="product.html">Products <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="contact.html">Contact us</a>
                </li>
              </ul>
              <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                  <a class="nav-link" href="#">Login</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="bsl.html">Register</a>
                </li>
              </ul>
            </div>
          </nav>

<div class="row" id="about">
            <div class="col" align="center">
                <h2>About Us</h2>
                <p>We are dedicated to providing top-quality pharmaceutical products and exceptional customer service.
                    Pharmacy is the science and practice of discovering, producing, preparing, dispensing, reviewing and monitoring medications, aiming to ensure the safe, effective, and affordable use of medicines. It is a miscellaneous science as it links health sciences with pharmaceutical sciences and natural sciences. The professional practice is becoming more clinically oriented as most of the drugs are now manufactured by pharmaceutical industries. Based on the setting, pharmacy practice is either classified as community or institutional pharmacy. Providing direct patient care in the community of institutional pharmacies is considered clinical pharmacy.
                    The scope of pharmacy practice includes more traditional roles such as compounding and dispensing of medications. It also includes more modern services related to health care including clinical services, reviewing medications for safety and efficacy, and providing drug information with patient counselling. Pharmacists, therefore, are experts on drug therapy and are the primary health professionals who optimize the use of medication for the benefit of the patients.
                    An establishment in which pharmacy (in the first sense) is practiced is called a pharmacy (this term is more common in the United States) or chemists (which is more common in Great Britain, though pharmacy is also used).[citation needed] In the United States and Canada, drugstores commonly sell medicines, as well as miscellaneous items such as confectionery, cosmetics, office supplies, toys, hair care products and magazines, and occasionally refreshments and groceries.
                    In its investigation of herbal and chemical ingredients, the work of the apothecary may be regarded as a precursor of the modern sciences of chemistry and pharmacology, prior to the formulation of the scientific method.
                </p>
            </div>
        </div>
        <footer class=" text-center py-3 mt-4">
            <div class="container">
                <p>&copy; copyrights @2024 | Developed by BALAJI J</p>
            </div>
        </footer>
    </body>
</html>
login
<html>
    <head>
        <title>
            Register
        </title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
        <style>
            .navbar 
            {
                background-color: rgb(47, 8, 188); 
            }
            footer {
                position: fixed;
                bottom: 0;
                width: 100%;
                background-color: rgb(91, 241, 26);
                color: rgb(8, 8, 8);
                padding: 10px 0;
            }
        </style>
    </head>
    <body>

<nav class="navbar navbar-expand-lg navbar-dark bg-plum">
            <a class="navbar-brand" href="#">Pharmacy</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
        
<div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav mr-auto">
                <li class="nav-item">
                  <a class="nav-link" href="ph.html">Home</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="about.html">About us</a>
                </li>
                <li class="nav-item active">
                  <a class="nav-link" href="product.html">Products <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="contact.html">Contact us</a>
                </li>
              </ul>
              <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                  <a class="nav-link" href="#">Login</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="bsl.html">Register</a>
                </li>
              </ul>
            </div>
        </nav>

 <script>
            function sfn()
            {
                document.getElementById("result").innerText="Registration Successful";
            }
        </script>
 <br>
        <br>
        
<div>
            <b>User name :</b>
            <input type="email" id="e1"><br>
            <b>Enter email :</b>
            <input type="text" id="un"><br>
            <b>Mobile . no   :</b>
            <input type="number" id="n"><br>
            <div >
                <button class="btn btn-success" onclick="sfn()">Submit</button>
            </div><br>
            <b><p align="center" id="result"></p></b>
        </div>

<footer class="text-center py-3 mt-4">
            <div class="container">
                <p>Designed and Developed by BALAJI J</p>
            </div>
        </footer>
    </body>

</html>
contact.html
<html>
    <head>
        <title>
            Contact
        </title>
        <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
        <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
        <style>
             .navbar 
            {
                background-color: rgb(47, 8, 188); 
            }
            footer {
                position: fixed;
                bottom: 0;
                width: 100%;
                background-color: rgb(91, 241, 26);
                color: rgb(8, 8, 8);
                padding: 10px 0;
            }
        </style>
    </head>
    <body>

<nav class="navbar navbar-expand-lg navbar-dark bg-plum">
            <a class="navbar-brand" href="#">Pharmacy</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
        
<div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav mr-auto">
                <li class="nav-item">
                  <a class="nav-link" href="ph.html">Home</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="about.html">About us</a>
                </li>
                <li class="nav-item active">
                  <a class="nav-link" href="product.html">Products <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="contact.html">Contact us</a>
                </li>
              </ul>
              <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                  <a class="nav-link" href="#">Login</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="bsl.html">Register</a>
                </li>
              </ul>
            </div>
        </nav>
       
<div class="row mt-4" id="contact" align="center">
            <div class="col-md-12">
                <h2>Contact Us</h2>
                <p>Email: contact@pharmacycompany.com <br><b>
                   Phone: +123 456 7890</p>
            </div>
        </div>
        <footer class=" text-center py-3 mt-4">
            <div class="container">
                <p>&copy; copyrights @2024 | Developed by BALAJI J</p>
            </div>
        </footer>
    </body>
</html>
phar.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .navbar 
            {
                background-color: rgb(47, 8, 188); 
            }
            footer {
                position: fixed;
                bottom: 0;
                width: 100%;
                background-color: rgb(91, 241, 26);
                color: rgb(8, 8, 8);
                padding: 10px 0;
            }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-plum">
    <a class="navbar-brand" href="#">Pharmacy</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
<div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="ph.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About us</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact us</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="bsl.html">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8" align="center">
        <h1>pharmacy</h1>
        <p>Together, we impact life and health with science. We offer one of the broadest portfolios in the industry for scientists, 
        best-in-class products for pharmaceutical development and manufacturing, and a fully integrated service organization to support CDMO and contract testing 
        across traditional and novel modalities. Our vision is a world where our innovative products, services, and digital offerings help create solutions for people
        globally and a sustainable future for generations to come.
        <p>Thank you for choosing Merck for your healthcare needs. We Are blessed and Happy to Be the reason for your healthier life.</p>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-plum text-black text-center">
    <div class="container">
      <p>&copy; copyrights @2024 | Developed by BALAJI J/p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
product.html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Product</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
     .navbar 
            {
                background-color: rgb(47, 8, 188); 
            }
    body {
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      margin: 0;
      padding: 0;
      background: url('download.jpeg') no-repeat center center fixed;
      background-size: cover;
    }
    .content {
      flex: 1;
    }
   
    footer {
                position: fixed;
                bottom: 0;
                width: 100%;
                background-color: rgb(91, 241, 26);
                color: rgb(8, 8, 8);
                padding: 10px 0;
      }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-plum">
    <a class="navbar-brand" href="#">Pharmacy</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="ph.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About us</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="product.html">Products <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact us</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="bsl.html">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5 content">
    <div class="row">
      <div class="col-md-12" align="center">
        <h1>Our Products</h1>
        <div class="card-deck">
          <div class="card">
            <img src="2.jpeg" class="card-img-top" alt="Product 1" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 1</h5>
              <p class="card-text">Everherb Karela Jamun Juice - Helps Maintains Healthy Sugar Levels -Helps In Weight Management - 1l.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="1.jpeg" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 2</h5>
              <p class="card-text">Glutone Skin Brightenin Face Serum For Glowing And Radiant Skin 30ml</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="3o.jpeg" class="card-img-top" alt="Product 3" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 3</h5>
              <p class="card-text">Vansaar 45+ Diab Balance Juice Bottle Of 1 Ltr.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <div class="container">
        <p>&copy; copyrights @2024 | Developed by BALAJI J</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
'''



## OUTPUT:
![alt text](<Screenshot 2024-12-27 230832.png>)
![alt text](<Screenshot 2024-12-27 230847.png>)
![alt text](<Screenshot 2024-12-27 230901.png>)
![alt text](<Screenshot 2024-12-27 230911.png>)
![alt text](<Screenshot 2024-12-27 230158.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
