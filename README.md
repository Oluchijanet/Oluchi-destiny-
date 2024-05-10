<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive E-Commerce Website</title>
    <!-- Link To CSS -->
    <link rel="stylesheet" href="style.css">
    <!-- Box Icons -->
    <link rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/boxicons@latest/css/boxicons.min.css">

    <!-- Link Swiper's CSS -->
    <link
      rel="stylesheet"
      href="https://unpkg.com/swiper/swiper-bundle.min.css"
    />
</head>
<body>
    <!-- Navbar -->
    <header>
        <a href="#" class="logo"> <i class='bx bxs-t-shirt'></i> adidas</a>

        <ul class="navbar">
            <li><a href="#home">Home</a></li>
            <li><a href="#new">New Arrival</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#reviews">Reviews</a></li>
        </ul>

        <!-- Icons -->
        <div class="header-icons">
            <i class='bx bx-menu' id="menu-icon" ></i>
            <i class='bx bx-search' id="search-icon"></i>
            <i class='bx bx-cart-alt' id="cart-icon"></i>
            <i class='bx bx-user' id="user-icon"></i>

        </div>

        <!-- Search Box -->
        <div class="search-box">
            <input type="search" name="" id="" placeholder="Search Here...">
        </div>

        <!-- Cart Box-->
        <div class="cart">
            <!-- Box 1 -->
            <div class="box">
            <img src="img/new1.png" alt="">
            <div class="text">
                <h3>T-Shirt 14A</h3>
                <span>$50.05</span>
                <span>x1</span>
            </div>
            <i class='bx bxs-trash-alt' ></i>
        </div>
        <!-- Box 2 -->
        <div class="box">
            <img src="img/new2.png" alt="">
            <div class="text">
                <h3>T-Shirt 14A</h3>
                <span>$50.05</span>
                <span>x1</span>
            </div>
            <i class='bx bxs-trash-alt' ></i>
        </div>

        <h2>Total:  $100.10</h2>
        <a href="#" class="btn">Checkout</a>

        </div>

        <!-- User -->
        <div class="user">
            <h2>Login Now</h2>
            <input type="email" placeholder="Your Email...">
            <input type="password" name="" id="" placeholder="Password">
            <input type="submit" value="Login" class="login-btn">
            <p>Forget Password <a href="#">Reset Now</a></p>
            <p>Dont't have acoount <a href="#">Create One</a></p>
        </div>

    </header>
    <!-- Home -->
    <section class="home" id="home">
        <div class="home-text">
            <span>Shop Now</span>
            <h1>New Arrival of <br>Fresh Products</h1>
            <a href="#" class="btn">Shop Now</a>
        </div>
        <div class="home-img">
            <img src="img/home.png" alt="">
        </div>
    </section>
    <!-- New Arrival -->
    <section class="new" id="new">
        <div class="heading">
            <h1>New <span>Arrival</span></h1>
        </div>
        <div class="swiper new-arrival">
            <div class="swiper-wrapper">
                <div class="swiper-slide box">
                    <img src="img/new1.png" alt="">
                    <div class="content">
                        <a href="#" class="btn">Buy Now</a>
                    </div>
                </div>
                <div class="swiper-slide box">
                    <img src="img/new2.png" alt="">
                    <div class="content">
                        <a href="#" class="btn">Buy Now</a>
                    </div>
                </div>
                <div class="swiper-slide box">
                    <img src="img/new3.png" alt="">
                    <div class="content">
   …
