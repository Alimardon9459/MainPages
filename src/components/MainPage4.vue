<template>
    <div class="container  row justify-between q-pa-xl ">
        <div class="col-7">
            <div class=" content text-bold text-white">
                The World’s <span class="text-blue" >1st ICO</span> Platform <br>
                That Offers Rewards
            </div>
            <div class="text text-white q-mt-md">
                The platform helps investors to make easy to purchase and sell their tokens
            </div>
            <div>
                <q-img class="q-mt-xl" width="700px" src="http://demo.ovathemes.com/cryptlight/wp-content/uploads/2021/08/ilus-bner.png" alt=""/>
            </div>

        </div>
        <div class="col-5 row justify-end   ">
            <div class=" card q-pa-xl" >
                <div class="text-center text-h5">Pre-sale is Live Now</div>
                <div class="row justify-between q-mt-lg ">
                    <div class="card-bit bg-blue-grey-9 text-center ">
                         <div class=" time row justify-center items-center text-h6"><span>30</span></div>
                         <div class="time-text text-center">Days</div>
                    </div>
                    <div class="card-bit bg-blue-grey-9 text-center ">
                         <div class=" time row justify-center items-center text-h6"><span>30</span></div>
                         <div class="time-text text-center">Hours</div>
                    </div>
                    <div class="card-bit bg-blue-grey-9 text-center ">
                         <div class=" time row justify-center items-center text-h6"><span>30</span></div>
                         <div class="time-text text-center">Minutes</div>
                    </div>
                    <div class="card-bit bg-blue-grey-9 text-center ">
                         <div class=" time row justify-center items-center text-h6"><span>30</span></div>
                         <div class="time-text text-center">Seconds</div>
                    </div>                    
                </div>
                <q-separator class="q-mt-xl" color="grey-6" />
                <div class="text-center text-h5 q-mt-xl">Pre Sale</div>
                <div class="bg-blue-grey-9 q-mt-lg radio">
                    <div class="radio-slider">

                    </div>
                    <div>
                        <div></div>
                    </div>
                </div>

                <div class="btn-token-div q-mt-xl row justify-center    "> <q-btn padding="15px 30px" rounded    class="btn-token bg-blue">Purchase tokens</q-btn> </div>
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
        background: rgb(0, 0, 40);
        background-image: url("http://demo.ovathemes.com/cryptlight/wp-content/uploads/2021/08/bg-banner.png");
        background-size: cover;
        background-repeat: no-repeat;
        height: 800px;
    }
    .content{
        font-size: 48px;
    }
    .text{
        font-size: 18px;
    }
    .card{
        color: white;
        width: 80%;
        height: 85vh;
        border-radius: 2%;
        background: rgba(1, 1, 48, 0.727);
        border: 2px solid rgba(0, 72, 255, 0.487);

    }
    .card-bit{
        width: 65px;
        height: 65px;
        border-radius: 15%;
    }
    .time-text{
        width: 100%;
        margin-top: 10%;
    }
    .time{
        width: 100%;
        height: 100%;
    }
    .radio{
        width: 100%;
        height: 15px;
        border-radius: 10px;
    }
    .radio-slider{
        width: 65%;
        height: 100%;
        background: rgb(3, 73, 213);
        border-radius: 10px;
        animation-name: elongation;
        animation-duration: 5s;
    }
    @keyframes elongation{
        0%{
            width: 0%;

        }
        100%{
            width: 65%;
        }
    }
</style>