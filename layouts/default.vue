<template>
  <div>
    <Nuxt />
  </div>
</template>

<style>
html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0px;
  padding: 0px;
}

.article {
  align-content: center;
  text-align: center;
  font-size: 20px;
  margin-top: 100px;
  margin-bottom: 30px;
  color: #258c9e;
}

.article_title {
  font-weight: 400;
  font-size: 30px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 25px;
  margin-bottom: 0px;
}

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

.button--blue {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #258c9e;
  color: #258c9e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 5px;
  margin-right: 5px;
  margin-top: 3px;
  margin-bottom: 3px;
}

.button--blue:hover {
  color: #fff;
  background-color: #258c9e;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 5px;
  margin-right: 5px;
  margin-top: 3px;
  margin-bottom: 3px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

.link--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 5px;
  margin-right: 5px;
  margin-top: 20px;
  margin-bottom: 20px;
}

.link--grey:hover {
  color: #fff;
  background-color: #35495e;
}

.link--blue {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #258c9e;
  color: #258c9e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 5px;
  margin-right: 5px;
  margin-top: 20px;
  margin-bottom: 20px;
}

.link--blue:hover {
  color: #fff;
  background-color: #258c9e;
}

</style>
