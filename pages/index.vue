<template>
  <div class="container">
    <div>
      <div class="head_box">
        <div class="head_box_item">
          <img class="screenshot" src="/2023/pivot/screenshot_pivot.png" />
        </div>
        <div class="head_box_item">
            <div class="main_text_logo">
              <img class="logo" src="/2023/pivot/icon_croped.png" />
              <img class="name" src="/2023/pivot/pivot_name.png" />
            </div>
            <div class="main_text">
                  Pivot est un moteur de jeu 3D.
                  <br>
                  Son but est d'utiliser les ressources offertes par les cartes graphiques modernes de la manière la plus efficace possible.
                  <br>
                  Il propose des fonctionnalités comme le "ray tracing", ou le "physically  based rendering". 
                  <br>
                  Afin de proposer un outil le plus adaptable possible, Pivot est compatible avec les formats et standards de l'industrie, facilitant ainsi son intégration dans un projet.
                  <br><br>
                  Pivot engine est en cours de développement.
                  <br>
                  Accedez à notre démonstration actuelle et apprenez en plus sur le moteur Pivot ci-dessous.
            </div>
        </div>
      </div>

      <div class="multiArticle">
        
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

        <NuxtLink class="button--grey" to="/user_doc">Documentation utilisateur</NuxtLink>
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

.screenshot {
  width: 55vw;
  border-radius: 4px;
}

.name {
  width: clamp(120px, 12.5vw, 400px);
}

.logo {
  width: clamp(80px, 10vw, 400px);
}

.main_text_logo {
  margin-left: 1vw;
  margin-bottom: 0.3vw;
  text-align: left;
}

.main_text {
  margin-left: 3vw;
  text-align: left;
  color: #04648c;
  font-size: clamp(15px, 1.18vw, 25px);
}

.head_box {
  margin-top: 10vw;
  margin-bottom: 2vw;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  padding-left: 1.5vw;
}

.head_box_item {
  display: flex;
  flex-direction: column;
  justify-content: baseline;
}

</style>
