<template>
  <div>
    <div class="navbar-height"></div>
    <div class="navbar">
      <div class="contain-burger">
        <div class="burger"></div>
      </div>
      <nav class="nav">
        <img src="../assets/logotype.png" alt="Logotype" />
        <a href="#" class="navbar-link active">Accueil</a>
      </nav>
    </div>
    <nav class="vertical-navbar">
      <a href="#" class="nav-vertical-link">
        <span class="fas fa-globe fa-3x"></span>
        <p>Planètes</p>
      </a>
      <a href="#" class="nav-vertical-link">
        <span class="fas fa-rocket fa-3x"></span>
        <p>Véhicules</p>
      </a>
      <a href="#" class="nav-vertical-link">
        <span class="fab fa-reddit-alien fa-3x"></span>
        <p>Personnes</p>
      </a>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'NavbarComponent'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
