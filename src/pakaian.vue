<template>
    <div id="app">
      <!-- Navbar -->
      <nav class="navbar">
        <div class="container">
          <h1>Fashion Store</h1>
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Men</a></li>
            <li><a href="#">Women</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
          </ul>
        </div>
      </nav>
  
      <!-- Carousel -->
      <div class="carousel">
        <!-- Your carousel content here -->
        <img src="src/assets/Gambar.jpg" alt="Carousel Image 1">

      </div>
  
      <!-- Card -->
      <div class="card-container">
        <div class="card">
          <img src="product-1.jpg" alt="Product 1">
          <h3>Kemeja Pria</h3>
          <p>Deskripsi Kemeja Pria</p>
          <button>Tambahkan Ke Keranjang</button>
        </div>
        <div class="card">
          <img src="product-2.jpg" alt="Product 2">
          <h3>Pakaian Wanita</h3>
          <p>Deskripsi Gaun Wanita</p>
          <button>Tambahkan Ke Keranjang</button>
        </div>
        <!-- Add more cards here -->
      </div>
  
      <!-- Footer -->
      <footer class="footer">
        <div class="container">
          <p>&copy; 2024 Fashion Store. All rights reserved.</p>
        </div>
      </footer>
    </div>
  </template>
  
  <script>
  export default {
    name: 'App',
    // Add any necessary logic or data here
  }
  </script>
  
  <style>
  /* Global Styles */
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  
  body {
    font-family: Arial, sans-serif;
  }
  
  .container {
    width: 80%;
    margin: 0 auto;
    padding: 20px 0;
  }
  
  /* Navbar Styles */
  .navbar {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
  }
  
  .navbar h1 {
    float: left;
  }
  
  .navbar ul {
    float: right;
  }
  
  .navbar ul li {
    display: inline;
    margin-left: 20px;
  }
  
  .navbar ul li a {
    color: #fff;
    text-decoration: none;
  }
  
  /* Carousel Styles */
  .carousel {
    width: 100%;
    overflow: hidden;
    margin: 20px 0;
  }
  
  .carousel img {
    width: 100%;
  }
  
  /* Card Styles */
  .card-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
  }
  
  .card {
    width: 300px;
    margin-bottom: 20px;
    padding: 20px;
    border: 1px solid #ccc;
  }
  
  .card img {
    width: 100%;
    margin-bottom: 10px;
  }
  
  .card h3 {
    font-size: 20px;
    margin-bottom: 10px;
  }
  
  .card p {
    margin-bottom: 10px;
  }
  
  .card button {
    background-color: #333;
    color: #fff;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
  }
  
  /* Footer Styles */
  .footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
  }
  </style>
  