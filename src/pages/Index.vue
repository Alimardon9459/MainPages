<template >
  <div>
    <MainPage1/>
    <MainPage2/>
    <MainPage3/>
    <MainPage4/>
    <Stayl/>
  </div>
</template>
<script>
import { defineComponent } from "@vue/runtime-core";
import MainPage1 from "src/components/MainPage1.vue";
import MainPage2 from "src/components/MainPage2.vue";
import MainPage3 from "src/components/MainPage3.vue";
import MainPage4 from "src/components/MainPage4.vue";
import Stayl from "src/components/Stayl.vue";
export default defineComponent ({
    components: {
    MainPage1,
    MainPage2,
    MainPage3,
    MainPage4,
    Stayl
}
})
</script>
<style>

</style>
