<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>The Little Angle’s Bigger Coffee</title>

  <link rel="stylesheet" href="style.css"/>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

  <link rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"/>
</head>

<body>

  <!-- Loader -->
  <div id="loader">
    <div class="coffee-loader"></div>
  </div>

  <!-- Navbar -->
  <nav>
    <div class="logo">☕ The Little Angle’s Bigger Coffee</div>

    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#menu">Menu</a></li>
      <li><a href="#gallery">Gallery</a></li>
      <li><a href="#reviews">Reviews</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Hero -->
  <section class="hero" id="home">
    <div class="overlay"></div>

    <div class="hero-content">
      <h1>The Little Angle’s Bigger Coffee</h1>

      <p>
        Luxury Coffee Experience Like Never Before
      </p>

      <div class="hero-buttons">
        <a href="https://wa.me/918570096375" class="btn" target="_blank">
          Order Online
        </a>

        <a href="#reviews" class="btn btn2">
          Give Review
        </a>
      </div>
    </div>
  </section>

  <!-- About -->
  <section class="about" id="about">

    <div class="about-text">
      <h2>About Us</h2>

      <p>
        We serve handcrafted premium coffee, cold brews,
        Indian tea, and luxury café experiences with rich
        flavors and unforgettable taste.
      </p>
    </div>

    <div class="about-img">
      <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?q=80&w=1200&auto=format&fit=crop" alt="">
    </div>

  </section>

  <!-- Menu -->
  <section class="menu" id="menu">

    <h2>Our Premium Menu</h2>

    <div class="menu-container">

      <div class="card">
        <i class="fa-solid fa-mug-hot"></i>
        <h3>Hot Coffee</h3>
      </div>

      <div class="card">
        <i class="fa-solid fa-glass-water"></i>
        <h3>Cold Coffee</h3>
      </div>

      <div class="card">
        <i class="fa-solid fa-mug-saucer"></i>
        <h3>Latte</h3>
      </div>

      <div class="card">
        <i class="fa-solid fa-cup-hot"></i>
        <h3>Americano</h3>
      </div>

      <div class="card">
        <i class="fa-solid fa-heart"></i>
        <h3>Heart Coffee</h3>
      </div>

      <div class="card">
        <i class="fa-solid fa-snowflake"></i>
        <h3>Dalgona Coffee</h3>
      </div>

      <div class="card">
        <i class="fa-solid fa-mug-hot"></i>
        <h3>Cappuccino</h3>
      </div>

      <div class="card">
        <i class="fa-solid fa-leaf"></i>
        <h3>Iced Tea</h3>
      </div>

      <div class="card">
        <i class="fa-solid fa-mug-tea"></i>
        <h3>Indian Tea</h3>
      </div>

    </div>

  </section>

  <!-- Gallery -->
  <section class="gallery" id="gallery">

    <h2>Luxury Coffee Gallery</h2>

    <div class="gallery-container">

      <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93?q=80&w=1200&auto=format&fit=crop">

      <img src="https://images.unsplash.com/photo-1511920170033-f8396924c348?q=80&w=1200&auto=format&fit=crop">

      <img src="https://images.unsplash.com/photo-1494314671902-399b18174975?q=80&w=1200&auto=format&fit=crop">

      <img src="https://images.unsplash.com/photo-1521017432531-fbd92d768814?q=80&w=1200&auto=format&fit=crop">

    </div>

  </section>

  <!-- Reviews -->
  <section class="reviews" id="reviews">

    <h2>Customer Reviews</h2>

    <div class="review-container">

      <div class="review-card">
        <h3>★★★★★</h3>
        <p>
          Amazing luxury coffee experience and beautiful atmosphere.
        </p>
      </div>

      <div class="review-card">
        <h3>★★★★★</h3>
        <p>
          Best cold coffee and Indian tea in town.
        </p>
      </div>

      <div class="review-card">
        <h3>★★★★★</h3>
        <p>
          Stylish café with premium taste and fast service.
        </p>
      </div>

    </div>

    <a href="#" class="btn review-btn">
      Give Review
    </a>

  </section>

  <!-- Contact -->
  <section class="contact" id="contact">

    <h2>Contact Us</h2>

    <p><i class="fa-brands fa-whatsapp"></i> 8570096375</p>

    <p><i class="fa-solid fa-clock"></i> Open Daily : 9 AM - 11 PM</p>

    <div class="socials">
      <i class="fa-brands fa-instagram"></i>
      <i class="fa-brands fa-facebook"></i>
      <i class="fa-brands fa-youtube"></i>
    </div>

  </section>

  <!-- Footer -->
  <footer>
    The Little Angle’s Bigger Coffee © 2026
  </footer>

  <!-- WhatsApp Floating Button -->
  <a href="https://wa.me/918570096375"
     class="whatsapp"
     target="_blank">

     <i class="fa-brands fa-whatsapp"></i>
  </a>

  <script src="script.js"></script>

</body>
</html>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  scroll-behavior:smooth;
}

body{
  font-family:'Poppins',sans-serif;
  background:#0f0f0f;
  color:white;
}

/* Loader */

#loader{
  position:fixed;
  width:100%;
  height:100vh;
  background:#000;
  z-index:9999;
  display:flex;
  align-items:center;
  justify-content:center;
}

.coffee-loader{
  width:70px;
  height:70px;
  border:6px solid #c59d5f;
  border-top:6px solid transparent;
  border-radius:50%;
  animation:spin 1s linear infinite;
}

@keyframes spin{
  100%{
    transform:rotate(360deg);
  }
}

/* Navbar */

nav{
  width:100%;
  padding:18px 8%;
  position:fixed;
  top:0;
  z-index:1000;
  display:flex;
  justify-content:space-between;
  align-items:center;
  background:rgba(0,0,0,0.5);
  backdrop-filter:blur(10px);
}

.logo{
  font-size:22px;
  font-weight:700;
  color:#d4a762;
}

nav ul{
  display:flex;
  gap:25px;
  list-style:none;
}

nav ul li a{
  color:white;
  text-decoration:none;
  transition:0.3s;
}

nav ul li a:hover{
  color:#d4a762;
}

/* Hero */

.hero{
  height:100vh;
  background:url('https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?q=80&w=1600&auto=format&fit=crop');
  background-size:cover;
  background-position:center;
  position:relative;
  display:flex;
  justify-content:center;
  align-items:center;
  text-align:center;
}

.overlay{
  position:absolute;
  width:100%;
  height:100%;
  background:rgba(0,0,0,0.6);
}

.hero-content{
  position:relative;
  z-index:2;
}

.hero h1{
  font-size:65px;
  font-family:'Playfair Display',serif;
  color:#f5d08b;
}

.hero p{
  margin-top:20px;
  font-size:20px;
}

.hero-buttons{
  margin-top:35px;
}

.btn{
  padding:14px 30px;
  background:#c59d5f;
  color:black;
  text-decoration:none;
  border-radius:40px;
  margin:10px;
  font-weight:600;
  transition:0.4s;
}

.btn:hover{
  background:white;
  transform:translateY(-5px);
}

.btn2{
  background:transparent;
  border:2px solid #c59d5f;
  color:white;
}

/* About */

.about{
  padding:100px 8%;
  display:flex;
  gap:50px;
  align-items:center;
  flex-wrap:wrap;
}

.about-text{
  flex:1;
}

.about-text h2{
  font-size:45px;
  color:#d4a762;
  margin-bottom:20px;
}

.about-text p{
  line-height:1.8;
  color:#ccc;
}

.about-img{
  flex:1;
}

.about-img img{
  width:100%;
  border-radius:20px;
}

/* Menu */

.menu{
  padding:100px 8%;
  text-align:center;
}

.menu h2{
  font-size:45px;
  color:#d4a762;
  margin-bottom:50px;
}

.menu-container{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:25px;
}

.card{
  background:#1b1b1b;
  padding:40px 20px;
  border-radius:20px;
  transition:0.4s;
}

.card:hover{
  transform:translateY(-10px);
  background:#2a2a2a;
}

.card i{
  font-size:45px;
  color:#d4a762;
  margin-bottom:20px;
}

/* Gallery */

.gallery{
  padding:100px 8%;
  text-align:center;
}

.gallery h2{
  font-size:45px;
  color:#d4a762;
  margin-bottom:40px;
}

.gallery-container{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
}

.gallery-container img{
  width:100%;
  height:320px;
  object-fit:cover;
  border-radius:20px;
  transition:0.4s;
}

.gallery-container img:hover{
  transform:scale(1.05);
}

/* Reviews */

.reviews{
  padding:100px 8%;
  text-align:center;
}

.reviews h2{
  font-size:45px;
  color:#d4a762;
  margin-bottom:50px;
}

.review-container{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:25px;
}

.review-card{
  background:#1c1c1c;
  padding:30px;
  border-radius:20px;
}

.review-card h3{
  color:gold;
  margin-bottom:15px;
}

.review-btn{
  display:inline-block;
  margin-top:40px;
}

/* Contact */

.contact{
  padding:100px 8%;
  text-align:center;
}

.contact h2{
  font-size:45px;
  color:#d4a762;
  margin-bottom:25px;
}

.contact p{
  margin:15px 0;
  color:#ccc;
}

.socials{
  margin-top:25px;
}

.socials i{
  font-size:25px;
  margin:0 10px;
  color:#d4a762;
  cursor:pointer;
}

/* Footer */

footer{
  padding:20px;
  text-align:center;
  background:#000;
  color:#aaa;
}

/* WhatsApp */

.whatsapp{
  position:fixed;
  bottom:20px;
  right:20px;
  width:60px;
  height:60px;
  background:#25d366;
  color:white;
  border-radius:50%;
  display:flex;
  justify-content:center;
  align-items:center;
  font-size:30px;
  text-decoration:none;
}

/* Responsive */

@media(max-width:900px){

  .hero h1{
    font-size:42px;
  }

  nav{
    flex-direction:column;
    gap:15px;
  }

  nav ul{
    flex-wrap:wrap;
    justify-content:center;
  }

}

