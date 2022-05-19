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
        <div class="content-img-animatsiya">
            <div class="img-animatsiya-fast q-pa-lg row justify-between">
                <q-img width="22%" src="https://rstheme.com/products/wordpress/landing/bizup/assets/images/banner/bnr-ly1.png" alt=""/>
                <q-img width="22%" src="https://rstheme.com/products/wordpress/landing/bizup/assets/images/banner/bnr-ly2.png" alt=""/>
            </div>
            <div class="img-animatsiya-slow q-pa-xl row justify-between">
                <q-img width="20%" src="https://rstheme.com/products/wordpress/landing/bizup/assets/images/banner/bnr-ly3.png" />
                <q-img width="20%" src="https://rstheme.com/products/wordpress/landing/bizup/assets/images/banner/bnr-ly4.png" />
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
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
    .content-img-animatsiya{
        width: 100%;
        position: absolute;
        top:13%;
    }
    .img-animatsiya-slow{
        padding: 6%;
    }
</style>