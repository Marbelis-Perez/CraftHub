# CraftHub
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CraftHub</title>
    <link rel="stylesheet" href="Chh.css">
</head>


<body>


<nav>
    <div class="logo">
        <img src="Loggo de CH.png" alt="Logo de CraftHub">
        <span>CRAFTHUB</span>
    </div>

    <ul>
        <li><a href="#" class="active">Inicio</a></li>
        <li><a href="#">Categorías</a></li>
        <li><a href="#">Artesanos</a></li>
        <li><a href="#">Nosotros</a></li>
    </ul>

    <button class="btn-nav">Descargar App</button>
</nav>

<section class="hero">

    <div class="hero-text">
        <h1>
            Descubre.<br>
            Compra.<br>
            <span>Apoya lo auténtico.</span>
        </h1>

        <p>
            Conectamos la artesanía panameña con el mundo.
        </p>

        <div class="buttons">
            <button class="btn-red">Explorar</button>
            <button class="btn-outline">Ver Productos</button>
        </div>
    </div>

<div class="hero-image">
    <div class="hero-carousel">
        <img src="https://th.bing.com/th/id/R.ff8f7fc428ef4e6788181f804e4a2aff?rik=1xdIcaqz%2bprfGQ&pid=ImgRaw&r=0" class="active" alt="Artesanía 1">
        <img src="https://tse3.mm.bing.net/th/id/OIP.bGMUp-y1zXg5N_F9r7B9ZQHaE5?r=0&w=1024&h=678&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Artesanía 2">
        <img src="https://lp-cms-production.imgix.net/2022-07/Panama-Panama-City-Randy-Faris-GettyImages-523791660-RFE.jpg?auto=format&q=40&w=870&dpr=5" alt="Artesanía 3">
    </div>
</div>

<section class="section">

    <h2>Productos Destacados</h2>

  <div class="products-carousel">

        <div class="product-card">
            <div class="img">
                <img src="Molas.jpg" alt="Molas">
            </div>
            <h3>Molas</h3>
            <p>$25</p>
        </div>

        <div class="product-card">
            <div class="img">
                <img src="Sombreros tipicos.jpg" alt="Sombreros">
            </div>
            <h3>Sombreros</h3>
            <p>$18</p>
        </div>

        <div class="product-card">
            <div class="img">
                <img src="Ceramica.webp" alt="Cerámicas">
            </div>
            <h3>Cerámicas</h3>
            <p>$30</p>
        </div>

        <div class="product-card">
            <div class="img">
                <img src="Joyería.webp" alt="Joyería">
            </div>
            <h3>Joyería</h3>
            <p>$15</p>
        </div>

    </div>

</section>

<section class="section">

    <h2>Categorías</h2>

    <div class="categories">

        <div class="category"> Artesanías</div>
        <div class="category"> Arte</div>
        <div class="category"> Moda</div>
        <div class="category"> Cerámica</div>
        <div class="category"> Textiles</div>
        <div class="category"> Joyería</div>

    </div>

</section>

<section class="impact">

    <div>
        <h3>500+</h3>
        <p>Artesanos</p>
    </div>

    <div>
        <h3>3000+</h3>
        <p>Productos</p>
    </div>

    <div>
        <h3>13</h3>
        <p>Provincias</p>
    </div>

</section>

<footer>

    <h2>CRAFTHUB</h2>
    <p>Creativity with Purpose</p>
    <p>@crafthub.pa</p>

</footer>


<script>
const images = document.querySelectorAll(".hero-carousel img");
let index = 0;

setInterval(() => {
    images[index].classList.remove("active");
    index = (index + 1) % images.length;
    images[index].classList.add("active");
}, 3000);

window.addEventListener("scroll", () => {
    const nav = document.querySelector("nav");

    if (window.scrollY > 50) {
        nav.classList.add("shrink");
    } else {
        nav.classList.remove("shrink");
    }
});
</script>

</body>


</body>
</html>
