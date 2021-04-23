<template>
      <div class="navegacion">
        <nav class="contenedor">
            <a href="#">Recetas</a>
            <a href="#">Productos</a>
            <a href="#">Recomendaciones</a>
            <a href="#">Videos</a>
        </nav>
    </div>
</template>

<style scoped>

.navegacion nav {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr))
}

.navegacion {
  background-color: black;
  margin: 3rem 0;
}

.navegacion a {
  padding: 1rem;
  color: white;
  text-decoration: none;
  text-transform: uppercase;
  text-align: center;
}

.navegacion a:hover {
  background-color: #c9c84a;
  color: black;
}


</style>