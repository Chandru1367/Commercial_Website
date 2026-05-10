# Ex02 Commercial Website
## Date: 10.05.2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM

## Index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chandru Shop</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="style.css">
</head>

<body>

<!-- NAVBAR -->
<header>
    <div class="logo">Chandru Shop</div>
    <nav>
        <a href="#">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- HERO -->
<section class="hero">
    <div class="hero-content">
        <h1>Smart Gadgets for Modern Life</h1>
        <p>Smart Watches • Earbuds • Gaming Gear</p>
        <button>Explore</button>
    </div>
</section>

<!-- PRODUCTS -->
<section id="products" class="section">
    <h2>Featured Products</h2>

    <div class="products">
        <div class="card">
            <img src="https://m.media-amazon.com/images/I/71XA0QCW5lL._AC_UF1000,1000_QL80_.jpg">
            <h3>Smart Watch</h3>
            <p>₹2,499</p>
        </div>

        <div class="card">
            <img src="https://www.leafstudios.in/cdn/shop/files/1_c4f26d0d-4aa2-407d-9a3f-5f1838ffed5f_1024x1024.png?v=1773822784">
            <h3>Wireless Earbuds</h3>
            <p>₹1,999</p>
        </div>

        <div class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcu6TMUCYLBd9enb4ggLg2pBU3q_L972xXSw&s">
            <h3>Gaming Mouse</h3>
            <p>₹899</p>
        </div>
    </div>
</section>

<!-- ABOUT -->
<section id="about" class="section light">
    <h2>About Us</h2>
    <p>We provide high-quality gadgets with modern design and innovation.</p>
</section>

<!-- CONTACT -->
<section id="contact" class="section">
    <h2>Contact</h2>
    <input type="text" placeholder="Name">
    <input type="email" placeholder="Email">
    <button>Send</button>
</section>

<!-- FOOTER -->
<footer>
    <p>© 2026 Chandru Shop</p>
</footer>

</body>
</html>
```

## Style.css

```css
/* GLOBAL */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    background: #f5f7fb;
    color: #333;
}

/* NAVBAR */
header {
    display: flex;
    justify-content: space-between;
    padding: 15px 40px;
    background: white;
    position: sticky;
    top: 0;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
}

.logo {
    font-weight: bold;
    font-size: 22px;
}

nav a {
    margin-left: 20px;
    text-decoration: none;
    color: #333;
}

nav a:hover {
    color: #4facfe;
}

/* HERO */
.hero {
    height: 90vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;

    background:
    linear-gradient(rgba(255,255,255,0.6), rgba(255,255,255,0.9)),
    url("https://images.unsplash.com/photo-1519389950473-47ba0277781c");

    background-size: cover;
    background-position: center;
}

.hero-content {
    background: rgba(255,255,255,0.7);
    padding: 40px;
    border-radius: 15px;
}

.hero h1 {
    font-size: 40px;
}

.hero p {
    margin: 10px 0;
}

/* BUTTON */
button {
    padding: 10px 20px;
    border: none;
    background: #4facfe;
    color: white;
    border-radius: 25px;
    cursor: pointer;
}

button:hover {
    background: #00c6ff;
}

/* SECTION */
.section {
    padding: 70px 20px;
    text-align: center;
}

/* PRODUCTS */
.products {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
    margin-top: 30px;
}

/* CARD */
.card {
    width: 250px;
    background: white;
    padding: 20px;
    border-radius: 15px;
    transition: 0.3s;
    box-shadow: 0 4px 15px rgba(0,0,0,0.08);
}

.card img {
    width: 100%;
}

.card:hover {
    transform: translateY(-10px);
}

/* LIGHT SECTION */
.light {
    background: #eef3ff;
}

/* CONTACT */
input {
    display: block;
    margin: 10px auto;
    padding: 10px;
    width: 250px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

/* FOOTER */
footer {
    background: white;
    padding: 20px;
    text-align: center;
    margin-top: 20px;
}

/* RESPONSIVE */
@media (max-width: 768px) {
    .products {
        flex-direction: column;
        align-items: center;
    }

    .hero h1 {
        font-size: 28px;
    }
}

```

## OUTPUT

<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/3231f003-3414-4026-baed-c29e6c6948db" />

<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/006d3fb8-ddba-4086-a0a5-a9325f2799f4" />

<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/d2ad48e9-fac5-40c5-af6d-5e1cb5b17c42" />


## RESULT

The program for creating commercial website using CSS Flexbox is executed successfully.
