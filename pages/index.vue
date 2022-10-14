<template>
  <div class="container">
    <div>
      <div class="multiArticle">
        <div class="article">
          <div class="article_title">
          Bienvenue sur le site de Pivot Engine !
          </div>
          <div class="center">
            <div class="block">
              Pivot est un moteur de jeu 3D.
              <br>
              Son but est d'utiliser les ressources offertes par les cartes graphiques modernes de la manière la plus efficace possible.
              <br>
              Il propose des fonctionnalités comme le "ray tracing", ou le "physicaly  based rendering". 
              <br>
              Afin de proposer un outil le plus adaptable possible, Pivot est compatible avec les formats et standards de l'industrie, facilitant ainsi son intégration dans un projet.
              <br><br>
              Pivot engine est en cours de développement.
              <br>
              Accedez à notre démonstration actuelle et apprenez en plus sur le moteur Pivot ici.
            </div>
          </div>

        </div>
        <a
          href="https://github.com/ErinGrouille/Pivot_pre_demo"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          Jeu de démonstration
        </a>
        <a
          href="https://github.com/EIP-Pivot/demo-beta"
          target="_blank"
          rel="noopener noreferrer"
          class="button--blue"
        >
          Démonstration du moteur
        </a>

        <NuxtLink class="button--grey" to="/quick_start">Démarage rapide</NuxtLink>
        <NuxtLink class="button--blue" to="/tutorials">Tutoriels</NuxtLink>

        <div class="spacing"></div>

        <div class="article">
          <div class="article_title">
          Dernère mise à jour de l'équipe Pivot
          </div>
        "Nous développons actuellement la Beta de Pivot engine !"
        </div>

        <div class="spacing"></div>

        <div class="article">
          <div class="article_title">
            L'équipe de développement
          </div>
          L'équipe de développement de Pivot engine est composée d'élèves de l'école supèrieure d'informatique EPITECH, apprenez en plus sur chaque membre grace à nos présentations !
          <div class="small_spacing"></div>
          <team></team>
        </div>

        <div class="spacing"></div>

        <div class="article">
          <div class="article_title">
            Timeline du projet
          </div>
          <timeline></timeline>
        </div>
      
      </div>
    </div>
  </div>
</template>

<script>
import timeline from './timeline.vue'
export default {
  components: { timeline },}
</script>

<style>
.center {
  display: flex;
  justify-content: center;
}
.block {
  width: 70%;
}
</style>
