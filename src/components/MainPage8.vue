<template>
  <div class="">
    <q-carousel
    height="100vh"
      swipeable
      animated
      arrows
      v-model="slide"
      v-model:fullscreen="fullscreen"
      infinite
      autoplay=true
    >
      <q-carousel-slide :name="1">
        <div class="for-slide for-slide-1 row justify-center items-center ">
            <div class="w-50f text-white">
                <div class="w-100f row justify-center">
                    <q-img width="20%" src="https://corretto.qodeinteractive.com/wp-content/uploads/2018/04/h1-slider-img-1.png" />
                </div>
                <div class="w-100f text-h2 q-mt-lg row justify-center" >
                    COFFEE MASTERS
                </div>
                <div class="w-100f row q-mt-lg justify-center">
                    <q-img width="25%" src="	https://corretto.qodeinteractive.com/wp-content/uploads/2018/04/slider-separator-img.png" />
                </div>
                <div class="w-100f text-center text-grey-5 fs-16p row q-mt-lg justify-center" >
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Facilis, reiciendis, sed voluptates quo accusamus dolore eius corporis iure sint officiis cumque reprehenderit ducimus voluptate nemo aut dolorum accusantium laboriosam facere.
                </div>
                <div class="w-100f row q-mt-lg  justify-center">
                    <q-btn padding="18px 60px" outline >SHOP HERE </q-btn>
                </div>

            </div>
        </div>
      </q-carousel-slide>

      <q-carousel-slide :name="2">
        <div class="for-slide for-slide-2 row justify-center items-center ">
            <div class="w-50f text-white">
                <div class="w-100f row justify-center">
                    <q-img width="20%" src="https://corretto.qodeinteractive.com/wp-content/uploads/2018/04/h1-slider-img-1.png" />
                </div>
                <div class="w-100f text-h2 q-mt-lg row justify-center" >
                    COFFEE MASTERS
                </div>
                <div class="w-100f row q-mt-lg justify-center">
                    <q-img width="25%" src="	https://corretto.qodeinteractive.com/wp-content/uploads/2018/04/slider-separator-img.png" />
                </div>
                <div class="w-100f text-center text-grey-5 fs-16p row q-mt-lg justify-center" >
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Facilis, reiciendis, sed voluptates quo accusamus dolore eius corporis iure sint officiis cumque reprehenderit ducimus voluptate nemo aut dolorum accusantium laboriosam facere.
                </div>
                <div class="w-100f row q-mt-lg  justify-center">
                    <q-btn padding="18px 60px" outline >SHOP HERE </q-btn>
                </div>

            </div>
        </div>
      </q-carousel-slide>

      <q-carousel-slide :name="3">
        <div class="for-slide for-slide-3 row justify-center items-center ">
            <div class="w-50f text-white">
                <div class="w-100f row justify-center">
                    <q-img width="20%" src="https://corretto.qodeinteractive.com/wp-content/uploads/2018/04/h1-slider-img-1.png" />
                </div>
                <div class="w-100f text-h2 q-mt-lg row justify-center" >
                    COFFEE MASTERS
                </div>
                <div class="w-100f row q-mt-lg justify-center">
                    <q-img width="25%" src="	https://corretto.qodeinteractive.com/wp-content/uploads/2018/04/slider-separator-img.png" />
                </div>
                <div class="w-100f text-center text-grey-5 fs-16p row q-mt-lg justify-center" >
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Facilis, reiciendis, sed voluptates quo accusamus dolore eius corporis iure sint officiis cumque reprehenderit ducimus voluptate nemo aut dolorum accusantium laboriosam facere.
                </div>
                <div class="w-100f row q-mt-lg  justify-center">
                    <q-btn padding="18px 60px" outline >SHOP HERE </q-btn>
                </div>

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
      slide: ref(1),
      fullscreen: ref(false)
    }
  }
}
</script>
<style scoped>
    .for-slide-1{
        background-image: url(https://corretto.qodeinteractive.com/wp-content/uploads/2018/04/home-3-slider-image-1.jpg);
    }
    .for-slide-2{
        background-image: url(	https://corretto.qodeinteractive.com/wp-content/uploads/2018/04/home-3-slider-image-3-new.jpg);
    }
    .for-slide-3{ 
        background-image: url( https://corretto.qodeinteractive.com/wp-content/uploads/2018/04/home-3-slider-image-2.jpg);
    }
    .for-slide{ 
        background-size: cover;
        background-repeat: no-repeat;
        width: 100%;
        height: 100%;
        animation-name: shrink;
        animation-duration: 4s;
    }
    @keyframes shrink{
        0%{
            background-size:105% ;
            
        }
        100%{
            background-size: 100% ;
        }
    }
    .q-carousel__slide, .q-carousel .q-carousel--padding {
        padding: 0%;
    }
</style>
