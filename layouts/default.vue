<template>
  <div>
    <nuxt />
  </div>
</template>
<script>
import NavBar from "@/components/NavBar.vue";
export default {
  components:{
    NavBar,
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--lgreen {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #abc49c;
  color: #abc49c;
  text-decoration: none;
  padding: 10px 30px;
}

.button--lgreen:hover {
  color: #fff;
  background-color: #abc49c;
}

.button--brown {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #875c62;
  color: #875c62;
  text-decoration: none;
  padding: 10px 30px;
}

.button--brown:hover {
  color: #fff;
  background-color: #875c62;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
