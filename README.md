# Ex.07 Restaurant Website
## Date:

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
````
home.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Lamiya Restaurant</title>

    <!-- ✅ CORRECT CSS LINK -->
    <link rel="stylesheet" href="index.css">
</head>
<body>

<header>
    <h1>Lamiya Restaurant</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section class="main-content">
    <img src="images.jpg" alt="Lamiya Restaurant">
    <h2>Welcome to Lamiya Restaurant</h2>
    <p>Authentic flavors, modern dining experience, and cozy vibes.</p>
</section>

<footer>
    © Designed by RISITHA S
</footer>

</body>
</html>

menu.html
<!DOCTYPE html>
<html>
<head>
    <title>lamiya - Menu</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>Lamiya Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Our Menu</h2>
    <div class="menu-grid">
        <div class="card"><img src="images1.jpg"><p>Grilled Chicken -₹560</p></div>
        <div class="card"><img src="image 2.jpg"><p>chicken Pasta - ₹260</p></div>
        <div class="card"><img src="image 3.jpg"><p>chicken rice - ₹140</p></div>
        <div class="card"><img src="images 4.jpg"><p>chicken  Pizza - ₹350</p></div>
        <div class="card"><img src="image 5.jpg"><p>chicken Noodles - ₹160</p></div>
        <div class="card"><img src="image 6.jpeg"><p>chicken bbq - ₹250</p></div>
        <div class="card"><img src="image 7.jpg"><p>Chicken Curry - ₹320</p></div>
        <div class="card"><img src="image 8.jpg"><p>Prawn Fry - ₹350</p></div>
        <div class="card"><img src="image 9.jpg"><p>chicken Biriyani - ₹170</p></div>
        <div class="card"><img src="image 10.jpg"><p>mutton briyani - ₹220</p></div>
        <div class="card"><img src="image 11.jpeg"><p>Fresh Juice - ₹100</p></div>
        <div class="card"><img src="image 12.webp"><p>Coffee - ₹120</p></div>
    </div>
</section>

<footer>
    © Designed by RISITHA S.
</footer>
</body>
</html>

admin.html
<!DOCTYPE html>
<html>
<head>
    <title>Lamiya- Administration</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>Lamiya Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Meet Our Team</h2>
    <div class="team-grid">
        <div class="card"><img src="images 13.jpg" ><p>Person 1 - Head Chef</p></div>
        <div class="card"><img src="image 14.jpg"><p>Person 2 - Manager</p></div>
    </div>
</section>

<footer>
    © Designed by RISITHA S.
</footer>
</body>
</html>

conntact.html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Lamiya - Contact Us</title>
    <link rel="stylesheet" href="index.css">
    
        
        
</head>
<body>

<header>
    <h1>Lamiya Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <div class="contact-container">
        <h2>Contact Us</h2>
        <p><b>Address:</b> LAMIYA MULTICUSINE RESTAURANT-no 125,ondikupam,manavalanagar,thiruvallur</p>
        <p><b>Phone:</b> +91 6381802361</p>
        <p><b>Email:</b> lamiya multicusine.com</p>
        <p><b>Opening Hours:</b> Mon-Sun: 9:00 AM - 12:00 PM</p>
    </div>
</section>

<footer>
    © Designed by RISITHA S.
</footer>

</body>
</html>

index.css
ody {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #fff7f5;
    color: #333;
}
header {
    background-color: #d9791f; /* Primary color */
    color: white;
    padding: 20px;
    text-align: center;
}
nav {
    background-color: #333;
    text-align: center;
}
nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    padding: 8px;
    display: inline-block;
}
nav a:hover {
    background-color: #c52f2f; /* Accent color */
    color: #333;
}
section {
    padding: 40px;
    text-align: center;
}
h2 {
    color: #b33a3a;
    font-style:oblique;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.menu-grid, .team-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    max-width: 1000px;
    margin: 20px auto;
    text-align: center;
}
.card {
    background-color: rgb(229, 230, 234);
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    font-style: italic;
    color:#b33a3a;
    text-shadow:#f2c57c;
}
.card img {
    width: 80px;
    height: 100px;
    object-fit: cover;
    border-radius: 25px;
    align-items: center;
    border: #f2c57c;
    
}
footer {
    background-color:#333;
    color: white;
    
    text-align: center;
    padding: 15px;
}
contact-container {
            max-width: 800px;
            margin: 0 auto;
            text-align: left;
            padding: 20px;
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .contact-container h2 {
            text-align: center;
            color: #b33a3a;
        }
        .contact-container p {
            font-size: 18px;
            margin: 10px 0;
        }
        .contact-container b {
            color: #b33a3a;
        }
````


## OUTPUT:
<img width="1919" height="966" alt="Screenshot 2025-12-26 152922" src="https://github.com/user-attachments/assets/f7d7ebd8-24cc-4a26-a792-904cd2fb9df4" />
<img width="1903" height="959" alt="Screenshot 2025-12-26 154625" src="https://github.com/user-attachments/assets/985dcad9-d892-497b-aabf-6377008cbf62" />
<img width="1916" height="977" alt="Screenshot 2025-12-26 154639" src="https://github.com/user-attachments/assets/13ba53be-4650-49e7-b8af-431225d22ecf" />
<img width="1912" height="959" alt="Screenshot 2025-12-26 154656" src="https://github.com/user-attachments/assets/605f51fe-9250-40df-942e-7513b0a748c9" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
