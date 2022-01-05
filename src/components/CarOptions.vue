<template>
    <h2>Coche - Options API</h2>
    <p>Marca: {{brand}} </p>
    <p>Modelo: {{model}} </p>
    <p>Cilindraje: {{power}} </p>

    <button @click="upPower(1000)">Aumentar</button>
    <button @click="downPower">Disminuir</button>
</template>

<script>
export default {

    data() {
        return {
            brand:'Mazda',
            model:2020,
            power:60
        }
    },

    methods: {
        upPower(){
            console.log('Aumentar potencia -> '+ newPower)
        },
        downPower(){
            console.log('Bajar potencia')
        }
    },
}
</script>

<style>

</style>