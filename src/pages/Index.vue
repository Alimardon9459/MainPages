<template >
  <div>
    <MainPage1/>
    <MainPage2/>
    <MainPage3/>
    <CaruselforSanjaraka/>
  </div>
</template>
<script>
import { defineComponent } from "@vue/runtime-core";
import MainPage1 from "src/components/MainPage1.vue";
import MainPage2 from "src/components/MainPage2.vue";
import MainPage3 from "src/components/MainPage3.vue";
import CaruselforSanjaraka from "src/components/caruselforSanjaraka.vue";
export default defineComponent ({
    components: {
    MainPage1,
    MainPage2,
    MainPage3,
    CaruselforSanjaraka
}
})
</script>
<style>

</style>
