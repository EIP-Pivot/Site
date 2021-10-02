<template>
  <div class="container">
    <div>
      <a
        href="."
      >
      <img src="icon_croped.png" /></a>
      <h1 class="title">
        Pivot
      </h1>
      <h2 class="subtitle">
        game engine
      </h2>

      <div class="links">
        <a
          href="https://github.com/EIP-PixelUP/Documentation"
          target="_blank"
          rel="noopener noreferrer"
          class="button--blue"
        >
          Documentation
        </a>
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
          Download
        </a>
      </div>
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
