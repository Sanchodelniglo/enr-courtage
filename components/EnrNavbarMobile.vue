<template>
  <div class="d-md-none">
<!--    <div class="banner-logo">-->
<!--      <img src="~/assets/images/shared/enr-logo.png" alt="enr-courtage">-->
<!--    </div>-->
    <nav class="enr-navbar-mobile">
      <a href="/">Accueil</a>
      <a href="#">À propos</a>
      <a href="#">Solutions</a>
      <a href="#">Carrières</a>
      <a href="#">Contact</a>
    </nav>
  </div>
</template>

<style>
  /*.banner-logo {*/
  /*  display: flex;*/
  /*  justify-content: center;*/
  /*  align-items: center;*/
  /*  height: 50px;*/
  /*  width: 100%;*/
  /*  background-color: rgba(32,36,43,0.8);*/
  /*  position: fixed;*/
  /*  top: 0;*/
  /*  z-index: 3;*/
  /*}*/

  /*.banner-logo img {*/
  /*  height: 100%;*/
  /*}*/

  .enr-navbar-mobile {
    position: fixed!important;
    bottom: 0px;
    background-color: #ffeb01;
    height: 50px;
    color: white;
    font-size: smaller;
    z-index: 3;
  }

  .enr-navbar-mobile a {
    text-decoration: none;
    color: rgba(32,36,43,1);
  }
</style>
