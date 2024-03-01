<h1 style="color:green"> Products </h1>


<!-- Products Grid Container -->
<div class="products-grid">
  
<div class="card electronics">
        <img src="img/electro.jpeg" alt="Electronics">
        <div class="card-content">
            <h3>Electronics</h3>
            <p>Explore our range of electronic devices and gadgets.</p>
        </div>
    </div>
    <div class="card electronics">
        <img src="img/pc.jpeg" alt="Laptop">
        <div class="card-content">
            <h3>Laptop</h3>
            <p>Explore our range of electronic devices and gadgets.</p>
        </div>
    </div>
    <div class="card electronics">
        <img src="img/phone.jpeg" alt="Phone">
        <div class="card-content">
            <h3>Phone</h3>
            <p>Explore our range of electronic devices and gadgets.</p>
        </div>
    </div>
    <div class="card electronics">
        <img src="img/tv.png" alt="TV">
        <div class="card-content">
            <h3>TV</h3>
            <p>Explore our range of electronic devices and gadgets.</p>
        </div>
    </div>
</div>

<style>
    .products-grid {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 5px;
        color:white
    }

    .card {
        float: left;
        width: calc(70% - 5px);
        background-color: #f9f9f9;
        border: 1px solid #ddd;
        border-radius: 5px;
        padding: 30px;
      
    }

    .card img {
        width: 100%;
        border-radius: 5px;
      
    }

    .card-content {
        text-align: center;
     
    }
    h3{
        color:green
    }
     p{
        color:green
    }
</style>