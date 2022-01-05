
<template>
  <h1>Vue Js</h1>
  <Car/>
  <hr>
  <CarOptions />
  <hr>
  <Motos/>
</template>

<script>
import Car from './components/CarComposition.vue'
import Motos from './components/Motos.vue'
import CarOptions from './components/CarOptions'
export default {
    components:{ Car,Motos, CarOptions
      
    }
}
</script>

<style>

</style>