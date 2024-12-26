# Project Responsive Web Design using Bootstrap
## Date:26-12-2024

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
home.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribble</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
  <style>
    body {
      background: linear-gradient(135deg, #00aaff, #0044cc);
      color: #f1f1f1;
      font-family: 'Poppins', sans-serif;
    }

    .navbar {
      background-color: #003366;
    }
    .navbar .nav-link {
      color: #f1f1f1;
      font-weight: 600;
      margin: 0 10px;
      transition: color 0.3s;
    }
    .navbar .nav-link:hover {
      color: #ff6600;
    }

    .sorting-navbar {
      background-color: #004488;
      color: #f1f1f1;
      padding: 10px 0;
    }
    .sorting-navbar .nav-link {
      color: #f1f1f1;
      font-weight: 600;
      margin: 0 10px;
      border: 2px solid transparent;
      border-radius: 5px;
      padding: 5px 15px;
      transition: background-color 0.3s, color 0.3s;
    }
    .sorting-navbar .nav-link:hover {
      background-color: #ff6600;
      color: white;
    }

    .card {
      border: none;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.5);
    }
    .card img {
      height: 150px;
      border-top-left-radius: 15px;
      border-top-right-radius: 15px;
      object-fit: cover;
    }
    .card-body {
      background-color: #003366;
      color: #f1f1f1;
      text-align: center;
      padding: 15px;
    }

    footer {
      margin-top: 50px;
      background-color: #003366;
      color: #f1f1f1;
      padding: 20px;
    }

    .contact-section {
      background-color: #004488;
      padding: 50px 0;
    }

    .contact-section h2 {
      color: #ff6600;
      text-align: center;
      margin-bottom: 30px;
      font-size: 2.5rem;
    }

    .btn-primary {
      background-color: #ff6600;
      border: none;
      transition: background-color 0.3s;
    }
    .btn-primary:hover {
      background-color: #cc5200;
    }
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand text-white" href="#"><i class="fas fa-basketball-ball"></i> Dribble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <div class="container my-5">
    <div class="row g-4">
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="f1.jpg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="f2.jpg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="f3.jpg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="f4.jpg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="f5.jpg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="f6.jpg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
          </div>
        </div>
      </div>
    </div>
  </div>

  <section id="contact" class="contact-section">
    <div class="container">
      <h2>Contact Us</h2>
      <form>
        <div class="mb-3">
          <label for="name" class="form-label">YOUR NAME</label>
          <input type="text" class="form-control" id="name" placeholder="Enter your name">
        </div>
        <div class="mb-3">
          <label for="email" class="form-label">YOUR EMAIL</label>
          <input type="email" class="form-control" id="email" placeholder="Enter your email">
        </div>
        <div class="mb-3">
          <label for="message" class="form-label">Message</label>
          <textarea class="form-control" id="message" rows="5" placeholder="Your message"></textarea>
        </div>
        <button type="submit" class="btn btn-primary w-100">Send</button>
      </form>
    </div>
  </section>

  <footer class="text-center py-3">
    <p>&copy; 2024 Dribble. All rights reserved.</p>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #00aaff, #0044cc);
            color: #f1f1f1;
        }
        header {
            background-color: #003366;
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            font-size: 2.5em;
            margin: 0;
            font-weight: bold;
        }
        section {
            padding: 20px;
            max-width: 800px;
            margin: 20px auto;
            background: #ffffff;
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
            border-radius: 12px;
        }
        section h2 {
            font-size: 2em;
            margin-bottom: 10px;
            color: #003366;
        }
        section p {
            line-height: 1.8;
            margin: 10px 0;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form label {
            margin: 10px 0 5px;
            font-weight: bold;
            color: #003366;
        }
        form input, form textarea, form button {
            padding: 12px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 6px;
            font-size: 1em;
            font-family: 'Poppins', sans-serif;
        }
        form button {
            background-color: #ff6600;
            color: white;
            border: none;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s;
        }
        form button:hover {
            background-color: #cc5200;
            transform: scale(1.05);
        }
        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1><i class="fas fa-envelope"></i> Contact Us</h1>
    </header>
    <section>
        <h2><i class="fas fa-comment-dots"></i> Get in Touch</h2>
        <p>If you have any questions, feedback, or just want to say hello, feel free to reach out to us using the form below. We'd love to hear from you!</p>
        <form>
            <label for="name">Name</label>
            <input type="text" id="name" name="name" placeholder="Your Name" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="Your Email" required>

            <label for="message">Message</label>
            <textarea id="message" name="message" rows="5" placeholder="Your Message" required></textarea>

            <button type="submit"><i class="fas fa-paper-plane"></i> Send Message</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Contact Us. All rights reserved.</p>
    </footer>
</body>
</html>


about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Nature</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #00aaff, #0044cc);
            color: #f1f1f1;
        }
        header {
            background-color: #003366;
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            font-size: 2.5em;
            margin: 0;
            font-weight: bold;
        }
        section {
            padding: 20px;
            max-width: 800px;
            margin: 20px auto;
            background: #0b0808;
            border-radius: 12px;
        }
        section h2 {
            font-size: 2em;
            margin-bottom: 10px;
            color: #139cc2;
        }
        section p {
            line-height: 1.8;
            margin: 10px 0;
        }
        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>About Nature</h1>
    </header>
    <section>
        <h2><i class="fas fa-leaf"></i> Our Connection to Nature</h2>
        <p>Nature is a vast and beautiful phenomenon that encompasses all living and non-living things on Earth. From the towering mountains and deep oceans to the smallest insects and microorganisms, nature's diversity is endless and awe-inspiring.</p>
        <p>Understanding and appreciating nature is essential for the survival of all species, including humans. It provides us with essential resources like air, water, and food, as well as inspiration and solace.</p>
    </section>
    <section>
        <h2><i class="fas fa-tree"></i> Why Protect Nature?</h2>
        <p>Protecting nature is crucial to maintaining the balance of ecosystems. Every species, no matter how small, plays a role in this balance. Deforestation, pollution, and climate change pose serious threats to the natural world, making conservation efforts more important than ever.</p>
        <p>By adopting sustainable practices and supporting conservation initiatives, we can ensure that future generations experience the beauty and benefits of nature.</p>
    </section>
    <footer>
        <p>&copy; 2024 About Nature. All rights reserved.</p>
    </footer>
</body>
</html>

```


## OUTPUT:
![alt text](<Screenshot (22).png>)
![alt text](<Screenshot (23).png>)
![alt text](<Screenshot (24).png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
