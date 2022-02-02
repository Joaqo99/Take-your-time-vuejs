<template>
  <div class="contenedor">
    <Reloj />
    <div class="menu-botones">
      <button>Start</button>
      <button>Reset</button>
    </div>
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

.contenedor{
  display: flex;
  height: 100vh;
  margin: auto 35%;
  justify-content: center;
  align-items: center;
  align-content: center;
  flex-wrap: wrap;
  text-align: center;
  box-sizing: border-box;
}
</style>
