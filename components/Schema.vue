<template>
  <section>
    <div class="container">

      <div class="row schema">
        <div class="col-sm-12 col-md-8 schema-header grey-bg">
          <h1>
            NOTRE INTERVENTION
          </h1>
        </div>
        <div class="col-sm-12 col-md-4 schema-header yellow-bg">
          <p>
            Notre expertise au service de votre projet, afin de vous proposer la meilleur solution.
          </p>
        </div>
        <div class="col-sm-6 col-md-3">
          <h2 class="card-title text-center">
            <font-awesome-icon :icon="{ prefix: 'far', iconName: 'handshake' }"/>
          </h2>
          <h6 class="card-subtitle mb-2 text-muted text-center">Rencontrons-nous</h6>
          <p class="card-text">
            Nous écoutons vos besoins,
            nous estimons la faisabilité,
            et nous trouvons ensemble
            votre solution
          </p>
        </div>
        <div class="col-sm-6 col-md-3">
          <h2 class="card-title text-center">
            <font-awesome-icon :icon="{ prefix: 'fas', iconName: 'walking' }"/>
          </h2>
          <h6 class="card-subtitle mb-2 text-muted text-center">Notre analyse</h6>
          <p class="card-text">
            ENR COURTAGE étudie
            votre dossier en détail afin
            de trouver l'interlocuteur
            idéal
          </p>
        </div>
        <div class="col-sm-6 col-md-3">
          <h2 class="card-title text-center">
            <font-awesome-icon :icon="{ prefix: 'fas', iconName: 'search-dollar' }"/>
          </h2>
          <h6 class="card-subtitle mb-2 text-muted text-center">Notre recherche</h6>
          <p class="card-text">
            Nous recherchons et mettons
            en concurrence les
            entreprises et vous trouvons
            la meilleure offre
          </p>
        </div>
        <div class="col-sm-6 col-md-3">
          <h2 class="card-title text-center">
            <font-awesome-icon :icon="{ prefix: 'fas', iconName: 'glass-cheers' }"/>
          </h2>
          <h6 class="card-subtitle mb-2 text-muted text-center">Nous nous occupons de tout</h6>
          <p class="card-text">
            L'ensemble des démarches
            sont gérées par nos services,
            et nous vous tenons informés
            de leur avancée.
            Vous êtes serein, et vous vous
            concentrez sur votre activité
          </p>
        </div>
      </div>
    </div>

  </section>
</template>

<style>
  .schema {
    margin-bottom: 4rem;
  }

  .schema-header {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 5rem;
    margin-bottom: 2rem;
  }

  .schema-header h1 {
    color: white;
    font-weight: bolder;
    margin: 0;
  }

  .schema-header p {
    color: #737373;
    margin: 0;
    text-align: right;
  }
</style>
