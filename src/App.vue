<template>
  <div id="app">
    <Container/>
  </div>
</template>

<script>
import Container from './container/index.vue';
export default {
  name: 'app',
  components: {
    Container
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
}
* {
    padding: 0;
    margin: 0;
}
html,
body {
    height: 100%;
}
a,
a:hover,
a:visited {
	text-decoration: none;
   color:#555555;
	}
  

</style>
