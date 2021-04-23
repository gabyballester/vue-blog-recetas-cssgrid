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

</style>