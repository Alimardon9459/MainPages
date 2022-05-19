<template>
  <div class="q-pa-md">
    <q-carousel
    animated
      v-model="slide"
      arrows
      navigation
      infinite
    >
      <q-carousel-slide :name="1"  >
        <div  class="row justify-between items-center" >
            <div style="border:5px solid black" class="my-card bg-red">
                
            </div>
            <div style="border:5px solid black" class="my-card bg-red">
                
            </div>
            <div style="border:5px solid black" class="my-card bg-red">
                
            </div>
            <div style="border:5px solid black" class="my-card bg-red">
                
            </div>
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="2"  >
        <div  class="row justify-between items-center" >
            <div style="border:5px solid black" class="my-card bg-red">
                
            </div>
            <div style="border:5px solid black" class="my-card bg-red">
                
            </div>
            <div style="border:5px solid black" class="my-card bg-red">
                
            </div>
            <div style="border:5px solid black" class="my-card bg-black">
                
            </div>
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="3"  >
        <div  class="row justify-between items-center" >
            <div style="border:5px  solid black;" class="my-card bg-red">
                
            </div>
            <div style="border:5px solid black" class="my-card bg-red">
                
            </div>
            <div style="border:5px solid black" class="my-card bg-black">
                
            </div>
            <div style="border:5px solid black" class="my-card bg-blou">
                
            </div>
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="4"  >
        <div  class="row justify-between items-center" >
            <div style="border:5px  solid black;" class="my-card bg-red">
                
            </div>
            <div style="border:5px solid black" class="my-card bg-black">
                
            </div>
            <div style="border:5px solid black" class="my-card bg-blue">
                
            </div>
            <div style="border:5px solid black" class="my-card bg-yellow">
                
            </div>
        </div>
      </q-carousel-slide>

    </q-carousel>
  </div>
</template>

<script>
import { ref } from 'vue'

export default {
  setup () {
    return {
      slide: ref(1)
    }
  },
  data() {
      return {
          imgs:[
            {img:""},
            {img:""},
            {img:""},
            {img:""},
          ]
      }
  },
}
</script>
<style scoped>
    .my-card{
        width: 20%;
        height: 360px;
    }
</style>