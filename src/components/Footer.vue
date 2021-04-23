<template>
  <footer class="footer">
    <div class="contenedor">
      <div class="widget">
        <h3>Recetas</h3>
        <nav class="menu">
          <a href="#">Comida mexicana</a>
          <a href="#">Pizzas</a>
          <a href="#">Postres</a>
          <a href="#">Comida Asiatica</a>
          <a href="#">Comida Rápida</a>
        </nav>
      </div>

      <div class="widget">
        <h3>Recetas</h3>
        <nav class="menu">
          <a href="#">Comida mexicana</a>
          <a href="#">Pizzas</a>
          <a href="#">Postres</a>
          <a href="#">Comida Asiatica</a>
          <a href="#">Comida Rápida</a>
        </nav>
      </div>

      <div class="widget">
        <h3>Recetas</h3>
        <nav class="menu">
          <a href="#">Comida mexicana</a>
          <a href="#">Pizzas</a>
          <a href="#">Postres</a>
          <a href="#">Comida Asiatica</a>
          <a href="#">Comida Rápida</a>
        </nav>
      </div>

      <div class="widget">
        <h3>Recetas</h3>
        <nav class="menu">
          <a href="#">Comida mexicana</a>
          <a href="#">Pizzas</a>
          <a href="#">Postres</a>
          <a href="#">Comida Asiatica</a>
          <a href="#">Comida Rápida</a>
        </nav>
      </div>
    </div>

    <p class="copyright">@2021 Receta Fácil by Gabriel Ballester</p>
  </footer>
</template>

<style scoped>
.footer {
  background-color: #c9c84a;
  padding-top: 3rem;
  text-align: center;
}

.footer .contenedor {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
}

.footer a {
  display: block;
  color: black;
  text-decoration: none;
  text-transform: uppercase;
  color: #525252;
  margin-bottom: 0.5rem;
}

.copyright {
  color: white;
  background-color: #282828;
  margin: 3rem 0 0 0;
  padding: 1rem;
  text-align: center;
}
</style>
