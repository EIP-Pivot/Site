<template>
<div class=timeline_container>
  <!-- Latest update -->
  <vue-timeline-update
    :date="new Date('2022-11')"
    title="lancement de Pivot"
    description="Lancement de la version 1.0 du moteur Pivot."
    category="Novembre 2022"
    icon="code"
    color="turquoise"
  />

  <vue-timeline-update
    :date="new Date('2022-09')"
    title="cinquième sprint"
    description="Création de documentation et de tutoriels pour permettre d’utiliser plus simplement le moteur. Amélioration continue de l’expérience utilisateur pour permettre au plus grand nombre de tester le moteur Pivot."
    category="Septembre à décembre 2022"
    icon="code"
    color="turquoise"
  />

  <vue-timeline-update
    :date="new Date('2022-09')"
    title="fin des retours utilisateurs"
    description="Fin de la période de retours utilisateurs sur la beta du projet Pivot."
    category="Septembre 2022"
    icon="code"
    color="turquoise"
  />
  
  <vue-timeline-update
    :date="new Date('2022-06')"
    title="appel aux volontaires"
    description="Début de l’appel aux volontaires pour recueillir des retours utilisateurs."
    category="Juin 2022"
    icon="code"
    color="black"
  />

  <vue-timeline-update
    :date="new Date('2022-05')"
    title="quatrième sprint"
    description="Ajout de nouvelles fonctionnalités aux moteurs nécessaires à la réalisation d’un jeu complet. Création du premier jeu de démonstration. Amélioration rapide de l’expérience utilisateur grâce aux nombreux retours de la bêta."
    category="Mai à septembre 2022"
    icon="code"
    color="black"
  />
  
  <vue-timeline-update
    :date="new Date('2022-05')"
    title="version beta"
    description="Publication de la version bêta du moteur Pivot."
    category="Mai 2022"
    icon="code"
    color="black"
  />
  
  <vue-timeline-update
    :date="new Date('2022-01')"
    title="troisième sprint"
    description="Développement d’une version bêta du moteur, permettant de réaliser des jeux basiques grâce à notre langage de scripting et notre éditeur de scène. Création de nombreuses démos techniques."
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
