<template>
    <div class="home">
      <section class="hero">
        <div class="hero-content">
          <h1>Selamat Datang di Halaman Home</h1>
          <p>cara mudah belanja lewat toko online</p>
          <a href="/shop" class="btn-primary">Belanja Sekarang</a>
        </div>
      </section>
  
      
    </div>
  </template>
  
  <style scoped>
  .home {
    background: linear-gradient(to left, #96B6C5, #ddbb86, #f7797d );
    padding: 40px;
    font-family: Arial, sans-serif;
  }
  
  .hero {
    background: url('/path/to/hero-image.jpg') center/cover no-repeat;
    color: #0b0606;
    text-align: center;
    padding: 60px 0;
    background-size: cover;
  }
  
  .hero-content {
    max-width: 600px;
    margin: 0 auto;
  }
  
  h1 {
    font-size: 3rem;
    margin-bottom: 20px;
  }
  
  p {
    font-size: 1.5rem;
    margin-bottom: 20px;
  }
  
  .btn-primary {
    display: inline-block;
    padding: 15px 30px;
    background-color: #FFCF96;
    color: black;
    border: none;
    border-radius: 5px;
    text-decoration: none;
    font-size: 1.5rem;
    transition: background-color 0.3s;
  }
  
  .btn-primary:hover {
    background-color: #FFCF96;
  }
  
  .featured-products {
    margin-top: 40px;
    text-align: center;
  }
  
  .product-list {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  
  .product-card {
    margin: 20px;
    padding: 20px;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 5px;
    text-align: center;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }
  
  .product-card img {
    max-width: 100%;
    height: auto;
    margin-bottom: 10px;
  }
  
  .product-card h3 {
    font-size: 2rem;
  }
  
  .product-card p {
    font-size: 1.5rem;
    margin-top: 10px;
}
</style>