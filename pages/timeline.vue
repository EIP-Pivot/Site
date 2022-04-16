<template>
<div class=timeline_container>
  <!-- Latest update -->
  <vue-timeline-update
    :date="new Date('2022-05')"
    title="Quatrième et Cinquième sprint"
    description="Utilisation du moteur pour réaliser de plus gros jeux et recueil de retours utilisateurs. Développement de nouvelles fonctionnalités, en priorisant les plus bloquants d’après les retours utilisateurs. Création de documentation et de tutoriels pour permettre d’utiliser plus simplement le moteur."
    category="Mai à Décembre"
    icon="code"
    color="turquoise"
  />
  
  <vue-timeline-update
    :date="new Date('2022-05')"
    title="version beta"
    description="Publication de la version bêta du moteur"
    category="Mai 2022"
    icon="code"
    color="turquoise"
  />
  
  <vue-timeline-update
    :date="new Date('2022-01')"
    title="troisième sprint"
    description="Développement d’une version bêta du moteur, permettant de réaliser des jeux basiques grâce à notre langage de scripting et notre éditeur de scène. Création d’un jeu de démonstration pour montrer les capacités du moteur."
    category="Janvier à Mai"
    icon="code"
    color="black"
  />
  
  <vue-timeline-update
    :date="new Date('2022-01')"
    title="changement de language pour le scripting"
    description="Décision prise suite au départ d’un membre de créer le langage de scripting en C++ comme le reste du moteur. Planification de la bêta."
    category="Janvier 2022"
    icon="code"
    color="black"
  />
  
  <vue-timeline-update
    :date="new Date('2021-10')"
    title="deuxième sprint"
    description="Prototype de langage de scripting en Rust. Amélioration du moteur de rendu graphique pour charger des modèles plus complexes."
    category="Octobre à Janvier"
    icon="code"
    color="black"
  />
  
  <vue-timeline-update
    :date="new Date('2021-10')"
    title="introduction du scripting"
    description="Décision de créer un langage de scripting pour développer des jeux avec notre moteur."
    category="Octobre 2021"
    icon="code"
    color="black"
  />
  
  <vue-timeline-update
    :date="new Date('2021-07')"
    title="premier sprint"
    description="Prototypage du moteur et de l’éditeur. Réalisation d’un moteur de rendu 3D, d’un système d’ECS basique, et d’un éditeur visuel."
    category="Juillet à Octobre"
    icon="code"
    color="black"
  />

  <vue-timeline-update
    :date="new Date('2021-07')"
    title="début du projet"
    description="Début du projet après l’abandon de notre projet précédent pixelUP."
    category="Juillet 2021"
    icon="code"
    color="black"
  />
  
</div>
</template>
