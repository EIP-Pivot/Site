<template>
  <div>
    <Nav></Nav>
    <Head></Head>
    <Nuxt />
    <Tail></Tail>
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
  font-size: clamp(15px, 2vw, 20px);
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

.container {
  margin: 0 auto;
  min-height: 10vw;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  width: 90%;
}

.article {
  align-content: center;
  text-align: center;
  font-size: clamp(15px, 2vw, 25px);
  margin-top: 3vw;
  margin-bottom: 3vw;
  color: #04648c;
  width: 100%;
}

.multiArticle {
  align-content: center;
}

.article_title {
  font-weight: 400;
  font-size: clamp(25px, 4vw, 40px);
  color: #35495e;
  word-spacing: 0.5vw;
  padding-bottom: 2vw;
  margin-bottom: 0px;
}

.spacing {
  margin-bottom: 10vw;
}

.small_spacing {
  margin-bottom: 5vw;
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
  margin-bottom: 1vw;
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
  margin-bottom: 1vw;
}

.button--blue:hover {
  color: #fff;
  background-color: #35495e;
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
  margin-bottom: 1vw;
}

.button--grey:hover {
  color: #fff;
  background-color: #494949;
}

.frame {
  border-color: #04648c;
  border-style: dashed;
}

.timeline_container {
  margin: 0 auto;
  min-height: 10vw;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center left;
  text-align: center;
  width: 90%;
}

.sub_section .article {
  align-content: center;
  text-align: center;
  font-size: clamp(10px, 2vw, 20px);
  margin-top: 3vw;
  margin-bottom: 3vw;
  color: #3b84a5d3;
  width: 100%;
}

.sub_section .article_title {
  font-weight: 400;
  font-size: clamp(20px, 4vw, 35px);
  font-style: oblique;
  color: #1e5b9c;
  word-spacing: 0.5vw;
  padding-bottom: 2vw;
  margin-bottom: 0px;
}

</style>