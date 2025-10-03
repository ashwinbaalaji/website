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
    <h2>Meet Our Team</h2>
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
    <h2>Contact Us</h2>
    <p><b>Address:</b> 123 dholakpur Street, Food City</p>
    <p><b>Phone:</b> +91 9876543210</p>
    <p><b>Email:</b> idlykadai@gmail.com</p>
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
    <h2>Our Colorful Menu</h2>
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
    <h2>About Us</h2>
    <p>
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
  background: #ffffff;
  color: #040202;
}

/* Header */
header {
  background: linear-gradient(90deg, #ff7eb3, #ff758c, #ff9770);
  color: rgb(255, 253, 253);
  padding: 15px;
  text-align: center;
}

nav {
  margin-top: 10px;
}
nav a {
  color: rgb(251, 246, 246);
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
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
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
  background: #000000;
  color: rgb(250, 248, 248);
  text-align: center;
  padding: 15px;
}


```
# OUTPUT:
<img width="1919" height="1141" alt="Screenshot 2025-10-03 215621" src="https://github.com/user-attachments/assets/78ed7205-8e3b-4186-a149-1e4540b11373" />
<img width="1919" height="1127" alt="Screenshot 2025-10-03 215649" src="https://github.com/user-attachments/assets/5b2905cf-4d4a-4ab3-b4b3-e925e6aece5f" />
<img width="1919" height="1127" alt="Screenshot 2025-10-03 215712" src="https://github.com/user-attachments/assets/6bfb22bb-94e6-44ef-a473-91997bacf427" />
<img width="1919" height="1110" alt="Screenshot 2025-10-03 215730" src="https://github.com/user-attachments/assets/dc6dffe0-89bf-46e5-a4b4-c098aefbfcc1" />





# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
