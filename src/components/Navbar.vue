<template>
  <nav class="navbar navbar-expand-lg navbar-light fixed-top">
    <div class="container px-4">
      <router-link class="navbar-brand" to="/">
        <img src="../assets/logo.png" alt="logo de suricata" />
      </router-link>
      <button class="navbar-toggler navbar-dark border-light" type="button" data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
        aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <router-link class="nav-link text-light" to="/">Inicio</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link text-light" to="/products">Productos</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link text-light" to="/contact">Contacto</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link text-light" to="/about">About</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>

<style scoped>
/* Estilos opcionales para el Navbar */
</style>

