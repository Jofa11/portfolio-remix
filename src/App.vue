<template>
<div class="background">

</div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
html,
body {
  width: 100%;
  height: 100%;
  margin: 0px;
  padding: 0px;
  overflow-x: hidden;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.background {
  background-image: url('../src/assets/white-clouds.jpeg');
  background-repeat: no-repeat;
  background-size: cover;
  width: 100%;
  height: 55em;
}
</style>
