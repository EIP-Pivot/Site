<template>
  <div class="container">
    <div>
      <a
        href="."
      >
      <Logo></Logo></a>
      <h1 class="title">
        Pivot
      </h1>

      <h2 class="subtitle">
        game engine
      </h2>

      <Nav></Nav>

      <div class="article">
        Welcome to Pivot Engine !
        <br>
        <br>
        This project is still in development.
        <br>
        Access our current Demo and learn more about the engine here.
      </div>

      <a
        href="https://github.com/ErinGrouille/Pivot_pre_demo"
        target="_blank"
        rel="noopener noreferrer"
        class="link--grey"
      >
        Demo
      </a>
      <a
        href="."
        target="_blank"
        rel="noopener noreferrer"
        class="link--blue"
      >
        Quick start
      </a>
      <a
        href="."
        target="_blank"
        rel="noopener noreferrer"
        class="link--grey"
      >
        Tutorials
      </a>

    <Tail></Tail>

    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 150px;
  color: #35495e;
  letter-spacing: 1px;
  padding-bottom: 0px;
  margin-bottom: 0px;
}

.subtitle {
  font-weight: 300;
  font-size: 30px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 25px;
  margin-bottom: 0px;
}

.links {
  padding-top: 20px;
}
</style>
