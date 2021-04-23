<template>
  <header class="header">
    <img src="@/assets/img/logo.jpg" class="logo" />
  </header>
</template>

<style scoped>
.header {
  padding-top: 3rem;
  padding-left: 3rem;
}
@media screen and (max-width: 768px) {
.header {
  height: 150px;
  padding-left: 0;
  display: flex;
  justify-content: center;
}
}
</style>