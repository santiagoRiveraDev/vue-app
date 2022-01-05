<template>
  <h2>Esta moto es mia</h2>
  <p>Marca {{brands[2]}} </p>
  <p>Modelo {{models[4]}} </p>
  <p>Color {{colors[0]}} </p>
  <p>Cilindraje {{powers[3]}} </p>
</template>

<script>
export default {

  setup() {

    const brands = ['Harley','Ducati','Honda','Suzuki','Yamaha']
    const models = [1987, 1990, 2002, 1999, 2021]
    const colors = ['Negro', 'Rojo', 'Azul', 'Blanca']
    const powers = [97, 110, 250, 600, 125]

    return{
      brands, models, powers, colors
    }
    
  }

}
</script>

<style>

</style>