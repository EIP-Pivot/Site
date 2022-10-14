<template>
    <div class="Head">
      <div class="head_box">
        <div class="head_box_item">
          <NuxtLink to="/">
              <Logo></Logo>
          </NuxtLink>
        </div>
        <div class="head_box_item">
          <h1 class="title">
              Pivot
          </h1>
          <h2 class="subtitle">
              game engine
          </h2>
        </div>
      </div>
    </div>
</template>

<style>
.Head {
  align-content: center;
  text-align: center;
}

.head_box {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  padding-left: 10vw;
}

.head_box_item {
  display: flex;
  flex-direction: column;
  justify-content: baseline;
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
  font-size: 18vw;
  color: #35495e;
}

.subtitle {
  font-weight: 300;
  font-size: 5vw;
  word-spacing: 1vw;
  padding-bottom: 5vw;
  color: #04648c;
  }
</style>