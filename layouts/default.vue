<template>
  <div>
    <Nuxt />
  </div>
</template>

<script>import ogImage from '../assets/game/meta.png';
export default {
  head () {
    return {
      meta: [
        { hid: 'og:image', property: 'og:image', content: this.BASE_URL+ ogImage }
      ]
    }
  },}
</script>


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
  margin: 0;
}

</style>
