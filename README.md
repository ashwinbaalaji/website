# Ex.07 Restaurant Website
# Date:03.10.2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
base.html:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>{{ title }}</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🍴 Idlykadai Restaurant</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <main>
    {{ content }}
  </main>

  <footer>
    <p>© 2025 Idlykadai Restaurant | Designed by <b>ASHWIN BAALAJI V K</b></p>
  </footer>
</body>
</html>
administration.html:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - Idlykadai</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🍴 Idlykadai Restaurant</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html" class="active">Administration</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="admin-team">
    <h2 style="color: white;">Meet Our Team</h2>
    <div class="grid">
      <div><img src="admin1.png"><p><b>Mr. Ashwin Baalaji V K</b><br>Head Chef</p></div>
      <div><img src="admin2.png"><p><b>Mr. Linda</b><br>Manager</p></div>
      <div><img src="admin3.png"><p><b>Mr. Raj</b><br>Assistant Chef</p></div>
      <div><img src="admin4 (2).png"><p><b>Mr. Emily</b><br>Marketing Head</p></div>
      <div><img src="admin5 (2).png"><p><b>Mr. Tom</b><br>Event Manager</p></div>
      <div><img src="admin6 (2).png"><p><b>Mr. Zoe</b><br>HR Head</p></div>
    </div>
  </section>

  <footer>
    <p>© 2025 Idlykadai Restaurant | Designed by <b>ASHWIN BAALAJI V K</b></p>
  </footer>
</body>
</html>

contact.html:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact - Idlykadai</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🍴 Idlykadai Restaurant</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html" class="active">Contact</a>
    </nav>
  </header>

  <section class="contact">
    <h2 style="color: white;">Contact Us</h2>
    <p style="color: white;"><b>Address:</b> 123 dholakpur Street, Food City</p>
    <p style="color: white;"><b>Phone:</b> +91 9876543210</p>
    <p style="color: white;"><b>Email:</b> idlykadai@gmail.com</p>
  </section>

  <footer>
    <p>© 2025 Idlykadai Restaurant | Designed by <b>ASHWIN BAALAJI V K</b></p>
  </footer>
</body>
</html>

menu.html:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - Idlykadai</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🍴 Idlykadai Restaurant</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html" class="active">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="menu-grid">
    <h2 style="color: white;">Our Colorful Menu</h2>
    <div class="grid">
      <div><img src="food1.png"><p>Chicken Burger — ₹260</p>
</div>
      <div><img src="food2.png"><p>Pizza — ₹260</p>
</div>
      <div><img src="food3.png"><p>Chicken leg — ₹260</p>
</div>
      <div><img src="food4.png"><p>French fries — ₹260</p>
</div>
      <div><img src="food5.png"><p>Hotdog — ₹260</p>
</div>
      <div><img src="food.6.png"><p>Shawarma — ₹260</p>
</div>
      <div><img src="food7.png"><p>Chicken roll — ₹260</p>
</div>
      <div><img src="food8.png"><p>Chicken nuggets — ₹260</p>
</div>
      <div><img src="food9.png"><p>wrap — ₹260</p>
</div>
      <div><img src="food10.png"><p>Onion rings — ₹260</p>
</div>
      <div><img src="food11.png"><p>Milkshake — ₹260</p>
</div>
      <div><img src="food12.png"><p>Veg biriyani — ₹260</p>
</div>
    </div>
  </section>

  <footer>
    <p>© 2025 Idlykadai Restaurant | Designed by <b>ASHWIN BAALAJI V K</b></p>
  </footer>
</body>
</html>

home.html:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - Idlykadai</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🍴 Idlykadai Restaurant</h1>
    <nav>
      <a href="home.html" class="active">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="banner">
    <h2>Welcome to Idlykadai Restaurant!</h2>
    <p>Serving happiness with colors & flavors 🌈</p>
  </section>

  <section class="intro">
    <h2 style="color: white;">About Us</h2>
    <p style="color: white;">
      At Idlykadai Restaurant, every dish tells a story. We bring together authentic flavors, 
      fresh ingredients, and vibrant presentation to create unforgettable dining experiences.
    </p>
  </section>

  <footer>
    <p>© 2025 Idlykadai Restaurant | Designed by <b>ASHWIN BAALAJI V K</b></p>
  </footer>
</body>
</html>


style.css:

/* General */
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #000000;
  color: #040202;
}

/* Header */
header {
  background: linear-gradient(90deg, #ff7eb3, #ff758c, #ff9770);
  color: rgb(0, 0, 0);
  padding: 15px;
  text-align: center;
}

nav {
  margin-top: 10px;
}
nav a {
  color: rgb(255, 254, 254);
  text-decoration: none;
  margin: 0 15px;
  font-weight: bold;
}
nav a.active {
  border-bottom: 2px solid yellow;
}

/* Banner */
.banner {
  background: url('Screenshot 2025-10-03 212928.png') no-repeat center/cover;
  color: rgb(255, 255, 255);
  padding: 80px 20px;
  text-align: center;
}
.banner h2 {
  font-size: 40px;
}

/* Sections */
section {
  padding: 40px;
  text-align: center;
}

/* Grid Layout */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 20px;
  margin-top: 20px;
}
.grid div {
  background: #ffffff;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(255, 255, 255, 0.1);
  padding: 15px;
  transition: transform 0.3s;
}
.grid div:hover {
  transform: translateY(-5px);
}
.grid img {
  width: 100%;
  border-radius: 10px;
}

/* Contact */
.contact p {
  font-size: 18px;
}

/* Footer */
footer {
  background: #ffffff;
  color: rgb(1, 1, 1);
  text-align: center;
  padding: 15px;
}


```
# OUTPUT:
<img width="1919" height="1125" alt="Screenshot 2025-10-03 223604" src="https://github.com/user-attachments/assets/130f7f49-987b-427a-b59e-c6f2ea23e8d4" />
<img width="1919" height="1121" alt="Screenshot 2025-10-03 223627" src="https://github.com/user-attachments/assets/5f7f5906-95a3-4302-8460-66b0da996228" />
<img width="1919" height="1128" alt="Screenshot 2025-10-03 223646" src="https://github.com/user-attachments/assets/21a3a137-7b9f-47e4-baa9-ffed2e89fe35" />
<img width="1919" height="1131" alt="Screenshot 2025-10-03 223704" src="https://github.com/user-attachments/assets/fc87a51f-6f9a-45fc-9ed5-ace9370e0910" />








# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
