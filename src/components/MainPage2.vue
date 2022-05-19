<template>
  <div class="container row justify-arund" >
      <div class="col-6 container-content ">
        <div class=" content-bit-big text-h3 text-bold text-indigo-10">
          Best Real Estate Company WordPress Theme
        </div>
        <div class=" q-mt-xl  content-bit text-grey-7">
          Create a fully functional property listing website with Homlisti the most customizable and usability real estate theme on the themeforest.
        </div>
        <div class=" q-mt-lg content-bit row justify-between ">
          <div class="bit-icons " v-for="biticon in biticons" :key="biticon">
            <q-img :src="biticon.img"/>
          </div>
        </div>
      </div>
      <div class="col-4">
        <q-img width="100%" src="	https://radiustheme.com/demo/wordpress/themes/homlisti/preview/media/gallery/banner-img_1.png" />
      </div>
  </div>
</template>
<script>
export default ({
  data() {
    return {
      biticons:[
        {
          img:"https://radiustheme.com/demo/wordpress/themes/homlisti/preview/media/icon/wordpress.png"
        },
        {
          img:"https://radiustheme.com/demo/wordpress/themes/homlisti/preview/media/icon/elementor.png"
        },
        {
          img:"https://radiustheme.com/demo/wordpress/themes/homlisti/preview/media/icon/classified-plugin.png"
        },
        {
          img:"https://radiustheme.com/demo/wordpress/themes/homlisti/preview/media/icon/customizer.png"
        },
      ]
    }
  },
})
</script>
<style scoped>
  .container{
    width: 100%;
    height: 100vh;
    background: linear-gradient(90deg, #e3f4f0 0%, #f7fffd 100%);
  }
  .content-bit-big{
    width: 100%;
  }
  .content-bit{
    width: 60%;
    line-height: 1.6;
    letter-spacing: 1.4px;
  }
  .bit-icons{
    width: 20%;
  }
</style>
