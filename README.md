# Project Responsive Web Design using Bootstrap
## Date:26-12-24

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Colorful Hotel</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: #f5f5f5;
    }
    .navbar {
      background-color: #ff6f61;
    }
    .navbar-brand, .nav-link {
      color: white !important;
    }
    .hero {
      background: linear-gradient(135deg, #ff6f61, #ff9a76);
      color: white;
      padding: 100px 0;
      text-align: center;
    }
    .card {
      border: none;
    }
    .card img {
      border-radius: 10px;
    }
    .footer {
      background-color: #333;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand" href="#">Hotel Bliss</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Rooms</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Facilities</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="hero">
    <div class="container">
      <h1>Welcome to Hotel Bliss</h1>
      <p>Your perfect getaway with luxurious rooms and top-notch facilities.</p>
      <a href="#rooms" class="btn btn-light btn-lg">Explore Rooms</a>
    </div>
  </div>

  <!-- Rooms Section -->
  <div class="container my-5" id="rooms">
    <h2 class="text-center mb-4">Our Rooms</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card">
          <img src="image1.png" class="card-img-top" alt="Room 1">
          <div class="card-body">
            <h5 class="card-title">Deluxe Room</h5>
            <p class="card-text">Experience the luxury with our well-furnished deluxe rooms.</p>
            <a href="#" class="btn btn-primary">Book Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="image2.png" class="card-img-top" alt="Room 2">
          <div class="card-body">
            <h5 class="card-title">Suite</h5>
            <p class="card-text">Perfect for families and groups, with spacious living areas.</p>
            <a href="#" class="btn btn-primary">Book Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="image.png" class="card-img-top" alt="Room 3">
          <div class="card-body">
            <h5 class="card-title">Standard Room</h5>
            <p class="card-text">Cozy and comfortable, ideal for solo travelers or couples.</p>
            <a href="#" class="btn btn-primary">Book Now</a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <div class="footer">
    <p>&copy; 2024 Hotel Bliss. All rights reserved.</p>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
## OUTPUT:
![alt text](<Screenshot 2024-12-26 144840.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
