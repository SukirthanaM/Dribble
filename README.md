# Project Responsive Web Design using Bootstrap
## Date:24.12.24

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
  <title>Dribbble</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
      .shot-card img {
      height: 200px;
      object-fit: cover;
    }
    .shot-card:hover {
      transform: scale(1.02);
      transition: transform 0.15s ease;
    }

  </style>
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#" title="Dribbble"></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#">Shots</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
        <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#">Sign In</a></li>
        <form class="d-flex me-3" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-dark" type="submit">Search</button>
          </form>
      </ul>
    </div>
  </div>
</nav>

 <div class="container">
     <div class="row g-4">
      <div class="col-md-4">
        <div class="card shot-card">
          <img src="1.jpg" class="card-img-top" alt="Shot">
          <div class="card-body">
            <h5 class="card-title">Forest</h5>
            <p class="card-text">Olivia Johnson</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shot-card">
          <img src="2.jpg" class="card-img-top" alt="Shot">
          <div class="card-body">
            <h5 class="card-title">Chess</h5>
            <p class="card-text">Amelia Smith</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shot-card">
          <img src="3.jpg" class="card-img-top" alt="Shot">
          <div class="card-body">
            <h5 class="card-title">Book </h5>
            <p class="card-text">Benjamin Clark</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shot-card">
          <img src="4.jpg" class="card-img-top" alt="Shot">
          <div class="card-body">
            <h5 class="card-title">Night Sky</h5>
            <p class="card-text">Lily Davis</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shot-card">
          <img src="5.jpg" class="card-img-top" alt="Shot">
          <div class="card-body">
            <h5 class="card-title">Plant</h5>
            <p class="card-text">Noah Taylor</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shot-card">
          <img src="6.jpg" class="card-img-top" alt="Shot">
          <div class="card-body">
            <h5 class="card-title">Top of Hill</h5>
            <p class="card-text">James White</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shot-card">
          <img src="7.jpg" class="card-img-top" alt="Shot">
          <div class="card-body">
            <h5 class="card-title">Artwork</h5>
            <p class="card-text">Alexander Lee</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shot-card">
          <img src="8.jpg" class="card-img-top" alt="Shot">
          <div class="card-body">
            <h5 class="card-title">Sail Boat</h5>
            <p class="card-text">Isabella Brown</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shot-card">
          <img src="9.jpg" class="card-img-top" alt="Shot">
          <div class="card-body">
            <h5 class="card-title">Sunset</h5>
            <p class="card-text">Grace Harris</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer>
    <h2 style="background-color: rgb(26, 54, 53);-webkit-text-fill-color: rgb(255, 255, 255); text-align: center; font-size: 18px; font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">Designed and developed by Sukirthana M</h2>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
## OUTPUT:
![alt text](<suki/dribb/static/Screenshot (49).png>)
![alt text](<suki/dribb/static/Screenshot (50).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
