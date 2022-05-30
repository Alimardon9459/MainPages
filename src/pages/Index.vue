<template >
  <div>
    <MainPage1/>
    <MainPage2/>
    <MainPage3/>
    <MainPage4/>
    <MainPage5/>
    <MainPage6/>
    <MainPage7/>
    <MainPage8/>
   
  </div>
</template>
<script>
import { defineComponent } from "@vue/runtime-core";
import MainPage1 from "src/components/MainPage1.vue";
import MainPage2 from "src/components/MainPage2.vue";
import MainPage3 from "src/components/MainPage3.vue";
import MainPage4 from "src/components/MainPage4.vue";
import MainPage5 from "src/components/MainPage5.vue";
import MainPage6 from "src/components/MainPage6.vue";
import MainPage7 from "src/components/MainPage7.vue";
import MainPage8 from "../components/MainPage8.vue";
export default defineComponent ({
    components: {
    MainPage1,
    MainPage2,
    MainPage3,
    MainPage4,
    MainPage5,
    MainPage6,
    MainPage7,
    MainPage8
}
})
</script>
<style>

</style>
