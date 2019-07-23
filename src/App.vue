<template>
  <div id="appinner">
    <!--<img src="./assets/logo.png">-->
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'appinner'
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
a{
    text-decoration: none;  
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
html, body, #appinner{
  width: 100%;
  height: 100%;
}
</style>
