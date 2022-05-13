<template >
  <div>
    <MainPage1/>
    <MainPage2/>
  </div>
</template>
<script>
import { defineComponent } from "@vue/runtime-core";
import MainPage1 from "src/components/MainPage1.vue";
import MainPage2 from "src/components/MainPage2.vue";
export default defineComponent ({
    components: { MainPage1, MainPage2 }
})
</script>
<style>

</style>
