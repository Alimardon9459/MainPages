<template>
    <div class="container row justify-center items-center">
        <div class="row justify-center wrap col-6 content">
            <div class="col-12 row justify-center">
                <q-img width="30%" src="https://rstheme.com/products/wordpress/landing/bizup/assets/images/logo.png" />
            </div>
            <div class="col-12 text-h3 text-center q-mt-lg text-white text-bold ">
                <span class="text-h3 text" >Consulting Business </span>
                <span class="text-h4 text" >WordPress Theme</span> 
            </div>
            <div class="text-center q-mt-lg col-12 row ">
                <div class="col-9 row justify-end" >
                    <q-btn 
                      class="bg-red-14 btn-register q-pt-md q-pb-md q-pl-xl q-pr-xl text-white "  size="18px" >
                        <q-img width="20px" src="https://rstheme.com/products/wordpress/landing/bizup/assets/images/download.png" class="text-white" />
                        PURCHASE NOW
                    </q-btn>
                </div>
                <div class="col-3 text-h5 row items-end justify-end ">
                    <span class="text-red-14">$29</span><span class="text-white">Only</span>
                </div>
            </div>
            <div class="col-9 row justify-end">
                <q-img class="" width="35%" src="https://rstheme.com/products/wordpress/landing/bizup/assets/images/banner/arrow.png" />
            </div>
        </div>
        <div class="gg">
            <div class="content-img-animatsiya row justify-center wrap items-center" :style="styles">
              <div :style="styles" class="img-animatsiya-fast  row justify-between">
                  <q-img width="22%" src="https://rstheme.com/products/wordpress/landing/bizup/assets/images/banner/bnr-ly1.png" alt=""/>
                  <q-img width="22%" src="https://rstheme.com/products/wordpress/landing/bizup/assets/images/banner/bnr-ly2.png" alt=""/>
              </div>
            </div>
            <div :style="stylesslow" class="content-img-animatsiya row justify-center wrap items-center">
              <div  id="slowimg" class="img-animatsiya-slow q-pa-xl row justify-between">
                  <q-img width="20%" src="https://rstheme.com/products/wordpress/landing/bizup/assets/images/banner/bnr-ly3.png" />
                  <q-img width="20%" src="https://rstheme.com/products/wordpress/landing/bizup/assets/images/banner/bnr-ly4.png" />
              </div>
            </div>
        </div>
    </div>
</template>
<script>

export default {
    data () {
      return {
        x: 0,
        y:0,
       
        viewportWidth: 1,
        viewportHeight: 1
      }
    },

    created () {
      this.updateViewportSize()
    },

    mounted () {
      document.addEventListener('mousemove', this.onMouseMove)
      window.addEventListener('resize', this.updateViewportSize)
    },

    unmounted () {
      document.removeEventListener('mousemove', this.onMouseMove)
      window.removeEventListener('resize', this.updateViewportSize)
    },

    computed: {
      styles () {
        return {
          left: percent(this.x, this.viewportWidth),
          top: percent(this.y, this.viewportHeight),
          
        }

        function percent (value, total) {
          return Math.round((value * 50 / total))-25 + 'px'
        }
      },
       stylesslow () {
        return {
          left: percent(this.x, this.viewportWidth),
          top: percent(this.y, this.viewportHeight),
          
        }

        function percent (value, total) {
          return Math.round((value * 20 / total))-10 + 'px'
        }
      }
    },

    methods: {
      onMouseMove (ev) {
        this.x = ev.clientX
        this.y = ev.clientY
      },

      updateViewportSize () {
        this.viewportHeight = window.innerHeight
        this.viewportWidth = window.innerWidth
      }
    }
}
</script>
<style scoped>
    .container{
        position: relative;
        width: 100%;
        height: 100vh; 
        background-image: url(	https://rstheme.com/products/wordpress/landing/bizup/assets/images/banner/banner.jpg);
        background-repeat: no-repeat;
        background-size: cover;
    }
    .text{
        letter-spacing: 6px;
    }
    .btn-register{
        border-radius: 0%;
    }
    .gg{
        height: 90vh;
        top:9%;
        position: absolute;
        width:100%;
        display: flex;
        justify-content:center ;
    }
    .content-img-animatsiya{
        height: 48%;
        width: 98%;
        position: absolute;
        display: flex;
        justify-content: center;
        
    }
    .img-animatsiya-slow{
        width: 97%;
        margin-top:300px
    }
    .img-animatsiya-fast{
      width: 95%;
    }
    
</style>