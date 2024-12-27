# Project Responsive Web Design using Bootstrap
## Date:27-12-2024

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
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>
    <div class="bg-dark">
        <nav class="navbar navbar-expand-lg">
            <div class="container-fluid">
                <a class="navbar-brand text-white" href="#">Dribbble</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav me-auto">
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle text-white" href="#" id="exploreDropdown" role="button"
                                data-bs-toggle="dropdown">
                                Explore
                            </a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Product Design</a></li>
                                <li><a class="dropdown-item" href="#">Web Design</a></li>
                                <li><a class="dropdown-item" href="#">Animation</a></li>
                            </ul>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle text-white" href="#" id="hireDropdown" role="button"
                                data-bs-toggle="dropdown">
                                Hire a Designer
                            </a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Browse designers</a></li>
                                <li><a class="dropdown-item" href="#">Post a job</a></li>
                                <li><a class="dropdown-item" href="#">Hiring on Dribbble</a></li>
                            </ul>
                        </li>
                        <a class="nav-link text-white" href="#">Find Jobs</a>
                    </ul>
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item"><a class="nav-link text-white" href="#">Sign Up</a></li>
                        <li class="nav-item bg-white rounded-4"><a class="nav-link text-dark" href="#">Login</a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>

    <div class="container-fluid text-center my-5">
        <h1 class="display-5">Unleash creativity and connect with the world's most talented designers on Dribbble.</h1>
        <p>Where creativity meets opportunity – Dribbble is your gateway to design brilliance.</p>
    </div>

    <nav class="navbar navbar-expand-lg navbar-light bg-white">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Popular</a>
            <div class="collapse navbar-collapse">
                <ul class="navbar-nav">
                    <li class="nav-item mx-3">
                        <a class="nav-link" href="#">Discover</a>
                    </li>
                    <li class="nav-item mx-3">
                        <a class="nav-link" href="#">Animation</a>
                    </li>
                    <li class="nav-item mx-3">
                        <a class="nav-link" href="#">Illustration</a>
                    </li>
                    <li class="nav-item mx-3">
                        <a class="nav-link" href="#">Web Design</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container mt-5">
        <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4 g-4">
            <div class="col">
                <div class="card">
                    <img src="original-655f7a50a321e0ea2f6e0ed871185e4b (1).webp" class="card-img-top" alt="Project 1">
                    <div class="card-body">
                        <h5 class="card-title">Ramotion</h5>
                        <p class="card-text">Modern Logo Design</p>
                        <p class="card-text">240 Likes</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <img src="original-1741ffba926e679b05dc81236d72cc69.webp" class="card-img-top" alt="Project 2">
                    <div class="card-body">
                        <h5 class="card-title">Awe Web Studio</h5>
                        <p class="card-text">Web Design</p>
                        <p class="card-text">800 Likes</p>
                    </div>
                </div>
            </div>
            <div class="col">
              <div class="card">
                  <img src="original-6de556f362d588c05a2295e733004c2f.webp" class="card-img-top" alt="Project 2">
                  <div class="card-body">
                      <h5 class="card-title">Visual diries</h5>
                      <p class="card-text">Web Design</p>
                      <p class="card-text">852 Likes</p>
                  </div>
              </div>
          </div>
          <div class="col">
            <div class="card">
                <img src="original-9c7fdbc95eadb9f3b082f6b859eb8b45.webp" class="card-img-top" alt="Project 2">
                <div class="card-body">
                    <h5 class="card-title">Pawly</h5>
                    <p class="card-text">Markwords branding</p>
                    <p class="card-text">926 Likes</p>
                </div>
            </div>
        </div>
        </div>
    </div>

    <footer class="text-white py-4 bg-dark">
        <div class="container text-center">
            <p>@2024 Dribble | Designed and developed by Mageshkumar</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>


```


## OUTPUT:
![Screenshot (26)](https://github.com/user-attachments/assets/bc6da4e6-547b-41be-be39-b01f575d761f)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
