<template>
    <div class="contenedor">
        <div class="contenedor-reloj">
            <div id="reloj">{{ display }}</div>
        </div>
        <div class="menu-botones">
            <button id="control" class="boton" type="button">Start</button>
            <button id="reset" class="boton reset" type="reset">Reset</button>
        </div>
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

.contenedor-reloj{
    display: flex;
    justify-content: center;
    align-items: center;
}
#reloj{
    color: #999;
    width: 100%;
}

.menu-botones{
    display: flex;
    width: 100%;
    justify-content: center;
    flex-wrap: nowrap;
}

.boton{
    margin: auto .5em;
    padding: 2px 1.5em;
    font-size: 20px;
    border: 2px solid #999;
    border-radius: 20px;
    background-color: #000;
    color: #999;
    cursor: pointer;
    font-weight: 700;
    width: 40%;
}


.boton:hover{
    border-color: #999;
    background-color: #999;
    color: #000;
}

.reset:hover{
    border-color: #e22;
    background-color: #e22;
    color: #000;
}
</style>