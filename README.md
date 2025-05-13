# Ex.07 Restaurant Website
## Date:05-05-2025
## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HOTEL BROTHERS</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans&family=Montserrat:wght@600&display=swap" rel="stylesheet">
</head>
<body>

  <!-- Header -->
  <header>
    <img src="image/logo1.png" alt="HOTEL BROTHERS LOGO" />
  </header>

  <!-- Navigation -->
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="about.html">About Us</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
    <a href="book.html">Book a Table</a>
  </nav>

  <!-- Promo Section -->
  <section class="promo">
    <h2>Special Weekend Discount - 30% Off</h2>
    <p>Come enjoy our exclusive weekend promotion! Our dishes are crafted using fresh, high-quality ingredients. Don’t miss out on this amazing offer!</p>
  </section>

  <!-- Cards Section -->
  <section class="cards">
    <!-- First Card -->
    <div class="card">
      <h3>Our New Menu</h3>
      <img src="image/raw.webp" alt="Our New Menu" />
      <p>Discover our brand-new menu, inspired by local and international flavors. We have something for every taste!</p>
      <a href="menu.html">Explore our new menu</a>
    </div>

    <!-- Second Card -->
    <div class="card">
      <h3>Book a Table</h3>
      <img src="image/table1.webp" alt="Book a Table" />
      <p>Reserve your table online with ease. Choose your date and time, and enjoy an unforgettable dining experience at Little Lemon.</p>
      <a href="book.html">Book your table now</a>
    </div>

    <!-- Third Card -->
    <div class="card">
      <h3>Our Opening Hours</h3>
      <img src="image/opening_hours1.webp" alt="Opening Hours" />
      <p>We are open every day to serve you! Check out our opening hours below:</p>
      <div class="hours">
        <p>Mon - Fri: 2:00 PM - 10:00 PM</p>
        <p>Sat: 2:00 PM - 11:00 PM</p>
        <p>Sun: 2:00 PM - 9:00 PM</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="footer-logo">
      <img src="image/logo1.png" alt="HOTEL BROTHERS" />
    </div>
    <p>Designed and developed by <a href="#">Sree Govind</a></p>
  </footer>

</body>
</html>
```
## menu.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Menu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #030303;
        }

        /* Logo Section */
        .logo-container {
            text-align: center;
            padding: 20px 10px 0;
            background-color: white;
        }

        .logo-container img {
            height: 80px;
        }

        nav {
            background-color: black;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }

        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
            font-weight: bold;
        }

        header {
            text-align: center;
            background-color: #03020c;
            padding: 20px;
        }

        header h1 {
            margin: 0;
            color: white;
        }

        .menu-section {
            padding: 30px;
            max-width: 1000px;
            margin: auto;
            background-color: #d3cbff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .menu-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .menu-item {
            background-color: #74708b;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            width: 200px;
        }

        .menu-item img {
            width: 100%;
            height: 150px;
            border-radius: 10px;
            object-fit: cover;
            margin-bottom: 10px;
        }

        .menu-item h3 {
            margin: 5px 0;
        }

        .menu-item p {
            font-size: 14px;
            color: white;
        }

        .price {
            font-weight: bold;
            color: white;
        }
    </style>
</head>
<body>

    <!-- Logo -->
    <div class="logo-container">
        <img src="image/logo1.png" alt="Logo">
    </div>

    <!-- Navigation -->
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admini.html">Administration</a>
        <a href="contact.html">Contact Us</a>
        <a href="book.html">Book a Table</a>
    </nav>

    <!-- Header -->
    <header>
        <h1>Our Menu</h1>
    </header>

    <!-- Menu Items -->
    <div class="menu-section">
        <div class="menu-grid">
            <div class="menu-item">
                <img src="image/dosa2.jpg" alt="Dosa">
                <h3>Dosa</h3>
                <p>Crispy and Yummy Dosa.</p>
                <div class="price">Rs. 30</div>
            </div>
            <div class="menu-item">
                <img src="image/dal2.jpg" alt="Dal Rice">
                <h3>Dal Rice</h3>
                <p>Traditional Indian Dal and Rice.</p>
                <div class="price">Rs. 50</div>
            </div>
            <div class="menu-item">
                <img src="image/VADA2.jpg" alt="Vada">
                <h3>Vada</h3>
                <p>Crispy and Crunchy Vada.</p>
                <div class="price">Rs. 10</div>
            </div>
            <div class="menu-item">
                <img src="image/cof2.jpg" alt="Coffee">
                <h3>Coffee</h3>
                <p>A delightful Coffee.</p>
                <div class="price">Rs. 10</div>
            </div>
            <div class="menu-item">
                <img src="image/cha2.jpg" alt="Chappathi">
                <h3>Chappathi</h3>
                <p>Soft Chappathi.</p>
                <div class="price">Rs. 15</div>
            </div>
            <div class="menu-item">
                <img src="image/noodles2.jpg" alt="Noodles">
                <h3>Noodles</h3>
                <p>Nice and long Noodles.</p>
                <div class="price">Rs. 100</div>
            </div>
        </div>
    </div>

</body>
</html>
```
## administration.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Administration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: rgb(5, 5, 5);
        }

        /* Logo Styling */
        .logo-container {
            text-align: center;
            padding: 20px 10px 0;
            background-color: white;
        }

        .logo-container img {
            height: 80px;
        }

        nav {
            background-color: #74708b;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }

        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }

        header {
            text-align: center;
            background-color: #74708b;
            padding: 20px;
        }

        .admin-section {
            padding: 30px;
            max-width: 800px;
            margin: auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .admin-section h2 {
            text-align: center;
            color: #74708b;
            margin-bottom: 20px;
        }

        .admin-team {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .team-member {
            background-color: #74708b;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            width: 200px;
        }

        .team-member img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 10px;
        }

        .admin-login {
            margin-top: 30px;
            text-align: center;
        }

        .admin-login input {
            padding: 10px;
            margin: 10px 5px;
            border: 1px solid #74708b;
            border-radius: 5px;
            font-size: 14px;
        }

        .admin-login button {
            padding: 10px 20px;
            background-color: #74708b;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .admin-login button:hover {
            background-color: #74708b;
        }
    </style>
</head>
<body>

    <!-- Logo -->
    <div class="logo-container">
        <img src="image/logo1.png" alt="Logo">
    </div>

    <!-- Navigation -->
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <!-- Header -->
    <header>
        <h1>Administration</h1>
    </header>

    <!-- Admin Content Section -->
    <div class="admin-section">
        <h2>VIEW THE BACK BONES</h2>
        <div class="admin-team">
            <div class="team-member">
                <h3>Renick</h3>
                <p>Manager</p>
            </div>
            <div class="team-member">
                <h3>Akash</h3>
                <p>Assistant Manager</p>
            </div>
            <div class="team-member">
                <h3>Govind</h3>
                <p>HR Head</p>
            </div>
        </div>

        <div class="admin-login">
            <h2>Admin Login</h2>
            <form>
                <input type="text" placeholder="Username" required>
                <input type="password" placeholder="Password" required>
                <button type="submit">Login</button>
            </form>
        </div>
    </div>

</body>
</html>
```
## book.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Advanced Booking - Restaurant</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: rgb(8, 3, 0);
    }

    .logo-container {
      text-align: center;
      padding: 20px;
      background-color: white;
    }

    .logo-container img {
      height: 80px;
    }

    nav {
      background-color: black;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 10px 15px;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #74708b;
    }

    header {
      background-color: #74708b;
      text-align: center;
      padding: 25px 15px;
    }

    header h1 {
      color: white;
      margin: 0;
    }

    .booking-section {
      background-color: white;
      max-width: 600px;
      margin: 40px auto;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 6px 14px rgba(0, 0, 0, 0.2);
    }

    .booking-section h2 {
      text-align: center;
      color: #74708b;
      margin-bottom: 20px;
    }

    .booking-form {
      display: flex;
      flex-direction: column;
      gap: 16px;
    }

    label {
      font-weight: bold;
    }

    input, select, button {
      padding: 12px;
      font-size: 16px;
      border: 1px solid #ccc;
      border-radius: 6px;
      transition: border-color 0.3s;
    }

    input:focus, select:focus {
      border-color: #74708b;
      outline: none;
    }

    button {
      background-color: #74708b;
      color: white;
      font-weight: bold;
      cursor: pointer;
      border: none;
      transition: background-color 0.3s;
    }

    button:hover {
      background-color: #74708b;
    }

    #confirmation {
      text-align: center;
      margin-top: 20px;
      color: #74708b;
      font-weight: bold;
      display: none;
    }

    /* Live preview */
    #preview {
      text-align: center;
      margin-top: 10px;
      color: #333;
      font-style: italic;
    }

    footer {
      background-color: black;
      color: white;
      text-align: center;
      padding: 15px 0;
      margin-top: 40px;
    }

    footer img {
      height: 40px;
      vertical-align: middle;
      margin-right: 10px;
    }

    footer p {
      display: inline;
      font-size: 14px;
    }

    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <!-- Logo -->
  <div class="logo-container">
    <img src="image/logo1.png" alt="Logo">
  </div>

  <!-- Navigation -->
  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact</a>
  </nav>

  <!-- Header -->
  <header>
    <h1>Book a Table</h1>
  </header>

  <!-- Booking Form -->
  <div class="booking-section">
    <h2>Reserve Your Table</h2>
    <form class="booking-form" id="bookingForm">
      <label for="name">Full Name:</label>
      <input type="text" name="name" id="name" placeholder="Your Full Name" required>

      <label for="email">Email Address:</label>
      <input type="email" name="email" id="email" placeholder="you@example.com" required>

      <label for="phone">Phone Number:</label>
      <input type="tel" name="phone" id="phone" placeholder="123-456-7890" required>

      <label for="guests">Guests:</label>
      <select name="guests" id="guests" required>
        <option value="" disabled selected>Choose number of guests</option>
        <option value="1">1 Guest</option>
        <option value="2">2 Guests</option>
        <option value="3">3 Guests</option>
        <option value="4">4 Guests</option>
        <option value="5">5 Guests</option>
        <option value="6+">6+ Guests</option>
      </select>

      <label for="date">Date:</label>
      <input type="date" name="date" id="date" required>

      <label for="time">Time:</label>
      <input type="time" name="time" id="time" required>

      <div id="preview"></div>

      <button type="submit">Book Now</button>
    </form>

    <div id="confirmation">✅ Your booking has been submitted!</div>
  </div>

  <!-- Footer -->
  <footer>
    <img src="image/logo1.png" alt="Logo">
    <p>© 2025 HOTEL BROTHERS | Designed by GOVIND</p>
  </footer>

  <script>
    const form = document.getElementById('bookingForm');
    const confirmation = document.getElementById('confirmation');
    const preview = document.getElementById('preview');
    const dateInput = document.getElementById('date');
    const timeInput = document.getElementById('time');

    form.addEventListener('submit', function(event) {
      event.preventDefault();
      confirmation.style.display = 'block';
      form.reset();
      preview.innerHTML = '';
    });

    // Live preview of date and time
    function updatePreview() {
      const date = dateInput.value;
      const time = timeInput.value;
      if (date && time) {
        preview.textContent = `📅 You selected: ${date} at ${time}`;
      } else {
        preview.textContent = '';
      }
    }

    dateInput.addEventListener('change', updatePreview);
    timeInput.addEventListener('change', updatePreview);
  </script>

</body>
</html>
```
## contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Contact Us - HOTEL BROTHERS</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #060606;
    }

    .logo-container {
      text-align: center;
      padding: 20px 10px 0;
      background-color: #fff;
    }

    .logo-container img {
      height: 80px;
    }

    nav {
      background-color: #212121;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 12px 0;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #ffd54f;
    }

    header {
      text-align: center;
      background-color: #74708b;
      padding: 30px 20px;
      color: white;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }

    .contact-section {
      background: white;
      padding: 40px 30px;
      max-width: 700px;
      margin: 30px auto;
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      animation: fadeIn 0.8s ease;
    }

    .contact-section h2 {
      text-align: center;
      color: #74708b;
      margin-bottom: 25px;
    }

    .contact-section form {
      display: flex;
      flex-direction: column;
      gap: 18px;
    }

    .contact-section input,
    .contact-section textarea {
      padding: 12px;
      font-size: 16px;
      border: 1px solid #ccc;
      border-radius: 6px;
      transition: border 0.3s;
    }

    .contact-section input:focus,
    .contact-section textarea:focus {
      border-color: #74708b;
      outline: none;
    }

    .contact-section textarea {
      resize: vertical;
      min-height: 100px;
    }

    .contact-section button {
      padding: 12px;
      font-size: 16px;
      background-color: #74708b;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    .contact-section button:hover {
      background-color: #74708b;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @media (max-width: 600px) {
      nav a {
        margin: 10px;
        display: block;
      }

      .contact-section {
        margin: 20px;
        padding: 20px;
      }
    }
  </style>
</head>
<body>

  <!-- Logo -->
  <div class="logo-container">
    <img src="image/logo1.png" alt="HOTEL BROTHERS LOGO">
  </div>

  <!-- Navigation -->
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <!-- Header -->
  <header>
    <h1>Contact HOTEL BROTHERS</h1>
    <p>We're here to help and hear from you!</p>
  </header>

  <!-- Contact Form Section -->
  <div class="contact-section">
    <h2>We Love to Hear from You!</h2>
    <form>
      <input type="text" name="name" placeholder="Your Full Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <input type="tel" name="phone" placeholder="Your Phone Number (optional)">
      <textarea name="message" placeholder="Your Message..." required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </div>

</body>
</html>
```
## style.css
```
body {
    margin: 0;
    font-family: 'Open Sans', sans-serif;
    background-color: #000000; /* Black background */
    color: #ffffff; /* Light text for contrast */
}

header {
    text-align: center;
    padding: 20px 0;
}

header img {
    height: 50px;
}

header h1 {
    display: inline-block;
    margin-left: 10px;
    font-family: 'Montserrat', sans-serif;
    color: #ffffff;
    vertical-align: middle;
}

nav {
    background-color: #74708b; /* Dark nav bar */
    padding: 10px 0;
    text-align: center;
}

nav a {
    color: #ffffff;
    text-decoration: none;
    margin: 0 25px;
    font-weight: bold;
    font-size: 16px;
    transition: color 0.3s;
}

nav a:hover {
    color: #ffcc00; /* Gold hover effect */
}

.promo {
    background-image: url('image/bg1.jpeg');
    background-size: cover;
    background-position: center;
    background-color: #74708b; /* Dark background */
    color: #6c6666;
    padding: 60px 20px;
    text-align: left;
    border-radius: 10px;
    margin: 20px auto;
    width: 90%;
    max-width: 1100px;
}

.promo h2 {
    font-size: 32px;
    margin-bottom: 10px;
    color: #d1ac16;
}

.promo p {
    max-width: 600px;
    color: #cccccc;
}

.cards {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin: 20px auto;
    max-width: 1100px;
}

.card {
    background-color: #74708b;
    padding: 20px;
    border-radius: 12px;
    width: 300px;
    box-shadow: 0 2px 8px rgba(255,255,255,0.1);
}

.card img {
    width: 100%;
    border-radius: 6px;
}

.card h3 {
    margin-top: 15px;
    color: #4e4315;
}

.card p {
    font-size: 14px;
    color: #cccccc;
}

.card a {
    color: #00bfff;
    text-decoration: underline;
    font-size: 14px;
}

footer {
    margin-top: 40px;
    padding: 20px;
    text-align: center;
    font-size: 14px;
    color: #888888;
    background-color: #111111;
}

footer a {
    text-decoration: none;
    color: #ff69b4;
    font-weight: bold;
}

.footer-logo img {
    height: 30px;
}

.hours {
    margin-top: 15px;
    font-size: 14px;
    color: #cccccc;
}
```
## OUTPUT:
![alt text](<Screenshot 2025-05-13 184404.png>)
![alt text](<Screenshot 2025-05-13 184418.png>)
![alt text](<Screenshot 2025-05-13 184433.png>)
![alt text](<Screenshot 2025-05-13 184449.png>)
![alt text](<Screenshot 2025-05-13 184834.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
