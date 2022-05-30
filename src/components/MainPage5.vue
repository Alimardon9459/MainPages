<template >
    <div class=" content text-bold ">
        <div class=" text-h2 text-white row wrap justify-center col-12 " >
            <div class="col-6  text-center mt-220p text-bold" >
                The quintessence of <br> rest
            </div>
        </div>
        <div class="row justify-center mt-9f">
            <div class="row col-7 " style="padding:0%" >
                <div class="row w-74f bg-white">
                    <div class=" q-pa-lg w-49f ">
                        <div>
                            <div class="fs-16p text-grey-6">CHECK IN - CHECK OUT</div> 
                            <div class="fs-16p q-mt-sm "> 26 May 2022 - 28 May 2022</div>
                             
                        </div>
                    </div>
                    <q-separator vertical  class="q-mt-lg" style=" height:55px; " />
                    <div class=" q-pa-lg w-49f bg-white">
                        <div>
                            <div class="fs-16p text-grey-6">ROOMS / GUESTS</div> 
                            <div class="fs-16p q-mt-sm "> 4 Room , 16 Adult , 8 Children</div>
                            
                        </div>
                    </div>
                </div>
                
                <div class=" row items-center fs-16p text-white justify-center w-25f bg-black h-100f">
                    <span class="text-center">CHECK <br> AVAILABITY</span>
                </div>
            </div>
        </div>
    </div>   
</template>
<script>
export default {
    
}
</script>
<style scoped>
    
    
    .content{
        width: 100%;
        height: 100vh;
        background-image: url(https://nuss.uxper.co/luxury-resort/wp-content/uploads/sites/6/2021/08/photo-1601701119533-fde20cecbf4e-16-1.jpeg);
        background-size: cover;
        animation-name: shrink;
        animation-duration: 5s;
        
        
    }
    @keyframes shrink{
        0%{
            background-size:120% ;
            
        }
        100%{
            background-size: 100% ;
        }
    }
    
</style>