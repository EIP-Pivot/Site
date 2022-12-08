<template>
  <div class="Nav">
    <div class="flex">
      <NuxtLink to="/">
        <img class="logo" src="/2023/pivot/icon_croped.png" />
      </NuxtLink>
      <div>
        <img class="name" src="/2023/pivot/pivot_name.png" />
      </div>
    </div>
    <div class="flex">
      <NuxtLink class="button--blue" to="/">Accueil</NuxtLink>
      <NuxtLink class="button--grey" to="/documentation">Documentation</NuxtLink>
      <a
        href="https://github.com/EIP-Pivot"
        target="_blank"
        rel="noopener noreferrer"
        class="button--blue"
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
  position: fixed;
  display: flex;
  justify-content: space-between;
  background-color: white;
  border-bottom: 1px solid #494949;
  width: 100%;
}

.logo {
  margin-top: 1.2vw;
  width: clamp(80px, 9vw, 400px);
}

.name {
  margin-top: 1vw;
  width: clamp(120px, 12vw, 400px);
}

.flex {
  display: flex;
}

.button--blue {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 1vw 2vw;
  margin-left: 0.5vw;
  margin-right: 0.5vw;
  margin-top: 1vw;
  margin-bottom: 3vw;
}

.button--blue:hover {
  color: #fff;
  background-color: #35495e;
}

.button--blue--important {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #fffcfc;
  background-color: #35495e;
  text-decoration: none;
  padding: 1vw 2vw;
  margin-left: 0.5vw;
  margin-right: 0.5vw;
  margin-top: 1vw;
  margin-bottom: 3vw;
}

.button--blue--important:hover {
  font-weight: bold;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #494949;
  color: #494949;
  text-decoration: none;
  padding: 1vw 2vw;
  margin-left: 0.5vw;
  margin-right: 0.5vw;
  margin-top: 1vw;
  margin-bottom: 3vw;
}

.button--grey:hover {
  color: #fff;
  background-color: #494949;
}

</style>