<template>
  <div>
    <header>
      <div class="overlay"></div>
      <video playsinline="playsinline" autoplay="autoplay" muted="muted" loop="loop">
        <source src="~/assets/videos/solar-pannels.mp4" type="video/mp4">
      </video>
      <div class="container h-100">
        <div class="d-flex h-100 text-center align-items-center">
          <div class="w-100 text-white">
            <h1 class="display-3">ENR | Courtage</h1>
            <p class="lead mb-0">1er réseau de Courtiers indépendants de France</p>
          </div>
        </div>
      </div>
    </header>
    <section class="my-5 half-section">
      <div class="container">
        <div class="row">
          <div class="col-md-8 mx-auto text-content">
            <p>Fondée par des professionnels expérimentés dans le monde des énergies renouvelables, ENR COURTAGE® a pour objectif de rapprocher les porteurs de projets, agriculteurs, artisans, chefs d’entreprises, élus et simples citoyens, des entreprises sérieuses présentent sur le marché français et européen, quel que les solutions recherchées.
            <p>En tant que Courtiers, nous agissons librement et indépendamment des investisseurs dans l’unique but de répondre pleinement aux souhaits de nos clients.</p>
            <p>Notre intervention est gratuite et vous garantit de bénéficier d’un interlocuteur expérimenté qui saura discuter d’éléments techniques avec les professionnels du monde des énergies renouvelables.</p>
            <p>A l’instar d’un courtier en prêt immobilier, nous agissons en votre nom auprès de tous les acteurs sérieux afin de trouver la meilleure solution technique et les conditions financières les plus intéressantes.</p>
          </div>
        </div>
      </div>
    </section>
    <Schema/>
  </div>
</template>


<script>
  import Logo from '~/components/Logo.vue'
  import Schema from '~/components/Schema.vue'

  export default {
    components: {
      Logo,
      Schema
    }
  }
</script>
<style>
  header {
    position: relative;
    background-color: black;
    height: 50vh;
    min-height: 25rem;
    width: 100%;
    overflow: hidden;
  }

  header video {
    position: absolute;
    top: 50%;
    left: 50%;
    min-width: 100%;
    min-height: 100%;
    width: auto;
    height: auto;
    z-index: 0;
    -ms-transform: translateX(-50%) translateY(-50%);
    -moz-transform: translateX(-50%) translateY(-50%);
    -webkit-transform: translateX(-50%) translateY(-50%);
    transform: translateX(-50%) translateY(-50%);
  }

  header .container {
    position: relative;
    z-index: 2;
  }

  header .overlay {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    background: rgb(10,8,33);
    background: -moz-radial-gradient(circle, rgba(10,8,33,1) 0%, rgba(112,112,112,0.6110819327731092) 74%, rgba(242,242,242,0.23573179271708689) 100%);
    background: -webkit-radial-gradient(circle, rgba(10,8,33,1) 0%, rgba(112,112,112,0.6110819327731092) 74%, rgba(242,242,242,0.23573179271708689) 100%);
    background: radial-gradient(circle, rgba(10,8,33,1) 0%, rgba(112,112,112,0.6110819327731092) 74%, rgba(242,242,242,0.23573179271708689) 100%);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#0a0821",endColorstr="#f2f2f2",GradientType=1);
    opacity: 0.3;
    z-index: 1;
  }

  @media (pointer: coarse) and (hover: none) {
    header {
      height: 50vh;
      background: url('https://comptroller.texas.gov/economy/fiscal-notes/2018/april/images/solar.jpg') black no-repeat center center scroll;
    }
    header video {
      display: none;
    }
  }

  .text-content {
    text-align: justify;
    text-justify: auto;
  }
</style>
