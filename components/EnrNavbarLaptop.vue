<template>
  <div class="d-none d-md-block">
    <nav class="enr-navbar-laptop">
      <a href="/">
        <img src="~/assets/images/shared/enr-logo.png" alt="enr-courtage">
      </a>
      <a href="/">Accueil</a>
      <a href="#">À propos</a>
      <a href="#">Solutions</a>
      <a href="#">Carrières</a>
      <a href="#">Contact</a>
    </nav>
  </div>
</template>

<style>
  .enr-navbar-laptop {
    position: fixed!important;
    top: 0px;
    background-color: #ffeb01;
    height: 70px;
    letter-spacing: 1px;
    z-index: 3;
  }

  .enr-navbar-laptop a {
    text-decoration: none;
    color: rgba(32,36,43,1);
  }

  .enr-navbar-laptop a img {
    height: 70px;
  }
</style>
