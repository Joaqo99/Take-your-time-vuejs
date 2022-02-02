<template>
    <div class="contenedor-reloj">
        <div id="reloj">{{ display }}</div>
    </div>
</template>

<script>
export default {
    data(){
        return{
            display: "00:00",
            running: false,
        }
    }
}
</script>

<style scoped>

</style>