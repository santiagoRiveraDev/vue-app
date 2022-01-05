<template>
  <!-- <h2>Coche</h2>
  <p>Marca: {{brand}} </p>
  <p>Modelo: {{model}} </p> -->

  <!--Condicionales-->
  <!-- <p>Potencias en zonas urbanas deben ser menores a 200cc</p>
  <ul>
    <template v-for="(power, index) in powers" key="index">
      <li v-if="power < 200">
        {{power}}
      </li>
    </template>
  </ul>

  <p>Potencias en zonas de carretera deben ser mayor o igual a 200</p>
  <ul>
    <template v-for="(power, index) in powers" key="index">
      <li v-if="power >= 200">
        {{power}}
      </li>
    </template>
  </ul> -->

<!--  <p>Potencias en zonas urbanas deben ser menores a 200cc</p>
  <ul>
    <template v-for="(power, index) in powers" key="index">
      <li v-if="power < 200"> Zona urbana: {{power}}</li>
      <li v-else>Zona de carretera: {{power}} </li>
    </template>
  </ul> -->

  <p>Potencias en zonas urbanas deben ser menores a 200cc</p>
  <ul>
    <template v-for="(power, index) in powers" key="index">
      <li v-if="power < 100">Zona rural: {{power}} </li>
      <li v-else-if="power === 100">Zona urbana: {{power}} </li>
      <li v-else>Zona de carretera: {{power}} </li>
    </template>
  </ul>

  <!--Ciclos-->
  <!-- <p>Color:
    <span v-for="color in colors">
      {{color}}
      </span> </p> -->
  <!----------------------------------------------->    
  <!-- <p>Color:
    <span v-for="(color, index) in colors" :key="index">
      {{index}}:{{color}}
    </span>
  </p>-->
  <!-----------------------------------------------
  <ul>
    <li v-for="(color, index) in colors" key="index">
      {{index}}:{{color}}
    </li>
  </ul>-->
  <!-- <p>Precio: {{prize}} </p>
  <p>Potencia: {{power}} </p>
  {{mensaje.title}} - {{mensaje.text}} -->



</template>

<script>
export default {
  //Manejo de variables
   /* data() {
   return {
      brand:'Audi',
      model:'1987',
      color:['Azul','Rojo','Negro'],
      prize: 38000,
      power: 1500,

      mensaje: {
        title:'Hola Mundo',
        text:'Esto es un texto' 
        return
      },
    }
  },*/

/*   setup(){
    const brand = 'Audi';
    const model = 1987;
    const color = ['Azul','Rojo','Negro'];
    const prize = 150000;
    const power = 1500;

    const mensaje = {
      title:'Bienvenidos',
      text:'a la primera API' 
    }

    return{
      brand,
      model,
      color,
      prize,
      power,
      mensaje
    }
  } */
  //Ciclos
  /* setup(){
    const brand = 'Mazda';
    const model = 1987;
    const colors = ['Azul','Rojo','Negro'];

    return{
      colors, model, brand
    }
  } */
  //Condicionales
  /* setup() {
    const brand = 'Ferrari'
    const model = 1987
    const powers = [150, 458, 1500, 450, 650, 100, 180, 200]

    return{
      brand, model, powers
    }
    
  } */
}
</script>

<style>

</style>