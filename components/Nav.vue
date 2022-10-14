<template>
  <div class="Nav">
    <img class="logo" src="/2023/pivot/icon_croped.png" />
    <div class="flex">
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
      <NuxtLink class="button--grey" to="/about">À propos</NuxtLink>
      <a
        href="https://github.com/EIP-Pivot/pivot/releases"
        target="_blank"
        rel="noopener noreferrer"
        class="button--blue--important"
      >
        Télécharger
      </a>
    </div>
  </div>
</template>

<style scoped>
.Nav {
  display: flex;
}
.logo {
  width: 9vw;
}
.flex {
  display: flex;
  justify-content: flex-end;
}
</style>