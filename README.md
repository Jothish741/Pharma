# Ex.10 Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KVL PRODUCTS - A PHARMA COMPANY</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    body {
      background-image: url('bgimage.png');
      background-size: cover;
      background-repeat: no-repeat;
      background-attachment: fixed;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="web.html">KVL PRODUCTS - A PHARMA COMPANY</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="web.html">HOMEPAGE</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="products.html" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              OUR PRODUCTS
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="products.html">MEDICINES</a>
              <a class="dropdown-item" href="products.html">VACCINES</a>
              <a class="dropdown-item" href="products.html">SUPPLEMENTS TABLETS</a>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">ABOUT KVL PRODUCTS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">CONTACT DETAILS</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Content Sections -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-6">
        <h2>WELCOME TO KVL PRODUCTS - A PHARMA COMPANY</h2>
        <p>KVL PRODUCTS IS A PHARMACEUTICAL COMPANY KNOWN FOR ITS COMMITMENT TO PROVIDING HIGH-QUALITY HEALTHCARE PRODUCTS. ESTABLISHED IN 2005, IT HAS STEADILY GROWN TO BECOME A PROMINENT PLAYER IN THE PHARMACEUTICAL INDUSTRY.</p>
        <p>THE COMPANY OFFERS A DIVERSE RANGE OF PHARMACEUTICAL PRODUCTS CATERING TO VARIOUS THERAPEUTIC SEGMENTS SUCH AS CARDIOVASCULAR, CENTRAL NERVOUS SYSTEM, GASTROENTEROLOGY, AND MORE. THEIR PRODUCT PORTFOLIO INCLUDES TABLETS, CAPSULES, INJECTABLES, SYRUPS, AND OTHER FORMULATIONS.</p>
        <p>KVL PRODUCTS ADHERES TO STRINGENT QUALITY STANDARDS IN MANUFACTURING PROCESSES TO ENSURE THE EFFICACY, SAFETY, AND RELIABILITY OF ITS PRODUCTS. THE COMPANY COMPLIES WITH REGULATORY REQUIREMENTS AND OFTEN GOES BEYOND INDUSTRY NORMS TO MAINTAIN HIGH-QUALITY STANDARDS.</p>
        <p>WHILE ROOTED IN ITS HOME MARKET, KVL PRODUCTS HAS EXPANDED ITS PRESENCE INTERNATIONALLY, EXPORTING ITS PHARMACEUTICAL PRODUCTS TO VARIOUS COUNTRIES. THIS GLOBAL REACH HAS HELPED THE COMPANY DIVERSIFY ITS REVENUE STREAMS AND TAP INTO NEW MARKETS.</p>
        <p>LOOKING AHEAD, KVL PRODUCTS IS FOCUSED ON IMPLEMENTING STRATEGIC INITIATIVES TO SUSTAIN ITS GROWTH TRAJECTORY. THIS MAY INCLUDE EXPANDING PRODUCT LINES, ENTERING NEW MARKETS, EMBRACING DIGITAL TECHNOLOGIES, AND EXPLORING OPPORTUNITIES FOR STRATEGIC ACQUISITIONS OR PARTNERSHIPS.</p>
      </div>
</body>
</html>


```

## OUTPUT:

![alt text](out-1.png)
![alt text](out-2.png)
![alt text](out-3.png)
![alt text](out-4.png)

## RESULT:
The program for responsive web design using Bootstrap is completed successfully.
