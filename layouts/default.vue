<template>
  <div>
    <Nuxt />
  </div>
</template>

<style lang="scss">
@import '~assets/scss/main.scss';
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  background-color: black;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
.links {
  padding-top: 15px;
  text-align: center;
  margin-bottom: 20px;
}
.content {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title {
  color: hsl(171, 100%, 41%);
  margin: 20px 20px auto;
}
p {
  margin: 5px 20px auto;
}
a {
  color: $primary;
}
</style>
