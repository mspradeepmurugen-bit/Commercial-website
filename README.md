# Commercial-website
# Ex02 Commercial Website
## Date:02/11/26

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
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elegance Store | Premium Shopping</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigation Bar -->
    <header>
        <nav class="navbar">
            <h2 class="logo">ELEGANCE<span>.</span></h2>

            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#categories">Categories</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>

            <a href="#products" class="nav-btn">Shop Now</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content">
            <p class="tagline">NEW COLLECTION 2026</p>
            <h1>Discover Your<br>Unique Style.</h1>
            <p>
                Explore premium collections designed
                for elegance, comfort and confidence.
            </p>
            <a href="#products" class="main-btn">Explore Collection</a>
        </div>
    </section>

    <!-- Categories -->
    <section class="categories" id="categories">
        <div class="section-heading">
            <p>EXPLORE OUR STORE</p>
            <h2>Shop By Category</h2>
        </div>

        <div class="category-container">
            <div class="category-card">
                <img src="https://images.unsplash.com/photo-1594633312681-425c7b97ccd1?w=600" alt="Women's fashion">
                <h3>Women's Wear</h3>
            </div>

            <div class="category-card">
                <img src="https://images.unsplash.com/photo-1483985988355-763728e1935b?w=600" alt="Fashion collection">
                <h3>New Arrivals</h3>
            </div>

            <div class="category-card">
                <img src="https://images.unsplash.com/photo-1490481651871-ab68de25d43d?w=600" alt="Fashion outfits">
                <h3>Premium Wear</h3>
            </div>
        </div>
    </section>

    <!-- Products -->
    <section class="products" id="products">
        <div class="section-heading">
            <p>OUR BEST COLLECTION</p>
            <h2>Featured Products</h2>
        </div>

        <div class="product-container">

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1610030469983-98e550d6193c?w=600" alt="Traditional outfit">
                <div class="product-info">
                    <h3>Traditional Collection</h3>
                    <p>Elegant and comfortable design</p>
                    <h4>₹1,299</h4>
                    <a href="#contact">Enquire Now</a>
                </div>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1595777457583-95e059d581b8?w=600" alt="Women's dress">
                <div class="product-info">
                    <h3>Designer Dress</h3>
                    <p>Perfect for every occasion</p>
                    <h4>₹1,599</h4>
                    <a href="#contact">Enquire Now</a>
                </div>
            </div>

            <div class="product-card">
                <img src="https://tse1.mm.bing.net/th/id/OIP.LQnvo7-ALR9O8o9WhFP-vAHaKL?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Fashion wear">
                <div class="product-info">
                    <h3>Premium Outfit</h3>
                    <p>Style meets comfort</p>
                    <h4>₹1,899</h4>
                    <a href="#contact">Enquire Now</a>
                </div>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1539109136881-3be0616acf4b?w=600" alt="Fashion dress">
                <div class="product-info">
                    <h3>Modern Collection</h3>
                    <p>Trendy everyday fashion</p>
                    <h4>₹999</h4>
                    <a href="#contact">Enquire Now</a>
                </div>
            </div>

        </div>
    </section>

    <!-- Offer Banner -->
    <section class="offer">
        <p>LIMITED TIME OFFER</p>
        <h2>Special Collection Sale</h2>
        <h3>Up To 30% OFF</h3>
        <a href="#products">Shop The Sale</a>
    </section>

    <!-- About Section -->
    <section class="about" id="about">
        <div class="about-image">
            <img src="https://images.unsplash.com/photo-1441986300917-64674bd600d8?w=800" alt="Fashion store">
        </div>

        <div class="about-content">
            <p>OUR STORY</p>
            <h2>Style That Defines You.</h2>
            <p>
                We believe fashion is more than clothing.
                It is a way to express your personality.
                Discover beautiful collections, quality
                products and a shopping experience you love.
            </p>
            <a href="#contact">Know More</a>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="section-heading">
            <p>GET IN TOUCH</p>
            <h2>Contact Us</h2>
        </div>

        <div class="contact-details">
            <h3>Visit Our Store</h3>
            <p>Address: Your Shop Address, Tamil Nadu</p>
            <p>Phone: +91 98765 43210</p>
            <p>Email: info@elegance.com</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <h2>ELEGANCE<span>.</span></h2>
        <p>Premium Fashion | Quality | Style</p>
        <p>© 2026 Elegance Store. All Rights Reserved.</p>
    </footer>

</body>
</html>
```
style.css
```

/* General Styling */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
    scroll-behavior: smooth;
}

body {
    background: #ffffff;
    color: #222;
}

/* Navigation */
header {
    background: #ffffff;
    padding: 20px 8%;
}

.navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo {
    font-size: 27px;
    letter-spacing: 2px;
}

.logo span,
footer span {
    color: #c59b62;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 30px;
}

.nav-links a {
    text-decoration: none;
    color: #333;
    font-size: 15px;
    transition: 0.3s;
}

.nav-links a:hover {
    color: #c59b62;
}

.nav-btn {
    background: #c59b62;
    color: white;
    padding: 12px 24px;
    text-decoration: none;
    border-radius: 4px;
}

/* Hero Section */
.hero {
    min-height: 550px;
    display: flex;
    align-items: center;
    padding: 70px 10%;
    background:
        linear-gradient(90deg, rgba(0,0,0,0.75), rgba(0,0,0,0.1)),
        url("https://images.unsplash.com/photo-1483985988355-763728e1935b?w=1600");
    background-position: center;
    background-size: cover;
    color: white;
}

.hero-content {
    max-width: 550px;
}

.tagline {
    color: #e6c18a;
    letter-spacing: 4px;
    margin-bottom: 20px;
}

.hero h1 {
    font-size: 60px;
    line-height: 1.15;
    margin-bottom: 20px;
}

.hero-content > p:not(.tagline) {
    font-size: 17px;
    line-height: 1.8;
    margin-bottom: 30px;
}

.main-btn {
    display: inline-block;
    background: #c59b62;
    color: white;
    text-decoration: none;
    padding: 15px 30px;
    border-radius: 4px;
}

/* Section Heading */
.section-heading {
    text-align: center;
    margin-bottom: 45px;
}

.section-heading p {
    color: #c59b62;
    letter-spacing: 3px;
    font-size: 13px;
    margin-bottom: 12px;
}

.section-heading h2 {
    font-size: 36px;
}

/* Categories */
.categories,
.products {
    padding: 80px 8%;
}

.category-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.category-card {
    position: relative;
    overflow: hidden;
}

.category-card img {
    width: 100%;
    height: 350px;
    object-fit: cover;
    transition: 0.4s;
}

.category-card:hover img {
    transform: scale(1.06);
}

.category-card h3 {
    text-align: center;
    padding: 20px;
    font-size: 22px;
}

/* Products */
.products {
    background: #f8f7f4;
}

.product-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 22px;
}

.product-card {
    background: white;
    transition: 0.3s;
    box-shadow: 0 3px 15px rgba(0,0,0,0.05);
}

.product-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
}

.product-card img {
    width: 100%;
    height: 270px;
    object-fit: cover;
}

.product-info {
    padding: 20px;
}

.product-info h3 {
    font-size: 18px;
    margin-bottom: 10px;
}

.product-info p {
    color: #777;
    font-size: 14px;
    margin-bottom: 15px;
}

.product-info h4 {
    color: #c59b62;
    font-size: 20px;
    margin-bottom: 18px;
}

.product-info a {
    display: inline-block;
    background: #222;
    color: white;
    padding: 11px 18px;
    text-decoration: none;
}

/* Offer */
.offer {
    background: #29231e;
    color: white;
    text-align: center;
    padding: 75px 20px;
}

.offer p {
    color: #e6c18a;
    letter-spacing: 4px;
}

.offer h2 {
    font-size: 38px;
    margin: 18px;
}

.offer h3 {
    font-size: 32px;
    color: #e6c18a;
    margin-bottom: 25px;
}

.offer a {
    display: inline-block;
    color: white;
    border: 1px solid #e6c18a;
    padding: 13px 28px;
    text-decoration: none;
}

/* About */
.about {
    display: grid;
    grid-template-columns: 1fr 1fr;
    align-items: center;
    gap: 60px;
    padding: 90px 10%;
}

.about-image img {
    width: 100%;
    height: 400px;
    object-fit: cover;
}

.about-content > p:first-child {
    color: #c59b62;
    letter-spacing: 3px;
}

.about-content h2 {
    font-size: 40px;
    margin: 20px 0;
}

.about-content > p:last-of-type {
    color: #777;
    line-height: 1.9;
    margin-bottom: 25px;
}

.about-content a {
    display: inline-block;
    background: #c59b62;
    color: white;
    padding: 13px 25px;
    text-decoration: none;
}

/* Contact */
.contact {
    padding: 80px 10%;
    background: #f8f7f4;
    text-align: center;
}

.contact-details {
    line-height: 2.2;
}

.contact-details h3 {
    margin-bottom: 15px;
    font-size: 23px;
}

/* Footer */
footer {
    background: #171717;
    color: white;
    text-align: center;
    padding: 35px 20px;
    line-height: 2;
}

/* Responsive Design */
@media (max-width: 900px) {
    .product-container {
        grid-template-columns: repeat(2, 1fr);
    }

    .nav-links {
        gap: 12px;
    }
}

@media (max-width: 650px) {
    header {
        padding: 18px 5%;
    }

    .navbar {
        flex-wrap: wrap;
        gap: 20px;
    }

    .nav-links {
        width: 100%;
        justify-content: center;
        flex-wrap: wrap;
    }

    .nav-btn {
        display: none;
    }

    .hero h1 {
        font-size: 42px;
    }

    .category-container,
    .product-container,
    .about {
        grid-template-columns: 1fr;
    }

    .categories,
    .products {
        padding: 55px 6%;
    }

    .about {
        padding: 55px 7%;
        gap: 30px;
    }

    .about-content h2 {
        font-size: 32px;
    }

    .section-heading h2 {
        font-size: 29px;
    }
}
```


## OUTPUT
![alt text](<Screenshot 2026-11-02 204715.png>)
![alt text](<Screenshot 2026-11-02 204731.png>)
![alt text](<Screenshot 2026-11-02 204743.png>)
![alt text](<Screenshot 2026-11-02 204756.png>)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
