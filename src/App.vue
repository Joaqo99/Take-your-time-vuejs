<template>
  <div class="contenedor">
    <Reloj />
  </div>
</template>

<script>

  import Reloj from "./components/Reloj.vue"

export default {
  name: 'App',
  components: { Reloj, },
  data(){}
}
</script>

<style>
#app {
  color: #aaa;
  font-size: 8em;
  font-family: 'Be Vietnam Pro', sans-serif;
  background: #000;
}
</style>
