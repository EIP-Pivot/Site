<template>
    <div class="Nav">
        <NuxtLink class="button--grey" to="/">Accueil</NuxtLink>
        <NuxtLink class="button--blue" to="/documentation">Documentation</NuxtLink>
        <a
          href="https://github.com/EIP-Pivot"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>
        <a
          href="https://github.com/EIP-Pivot/pivot/releases"
          target="_blank"
          rel="noopener noreferrer"
          class="button--blue"
        >
          Télécharger
        </a>
        <NuxtLink class="button--grey" to="/about">À propos</NuxtLink>
    </div>
</template>

<style scoped>
.Nav {
  margin-bottom: 8vw;
}
</style>