<template>
    <div class="q-pa-xl row justify-between">
        <div class="row items-center col-6  ">
            <div>
                <div class="text-blue">Welcome To Appie</div>
                <div class="text-h2 text-bold w-95f q-mt-lg text-indigo-10">
                    Manage it all, in this all new system.
                </div>
                <div class="q-mt-lg fs-18p text-grey-7">
                    Hanky panky lavatory up the duff jolly good cack brolly is chinwag zonked happy days sloshed.
                </div>
                <div class="q-mt-lg">
                    <q-btn class="bg-dark text-white"  padding="10px 15px" > <q-icon color="white" class="q-mr-md" name="apple"></q-icon> Download for iOS</q-btn>
                    <q-btn class="q-ml-lg" outline  padding="10px 15px" > <q-icon name="shop" class="q-mr-md" ></q-icon> Download for Android</q-btn>

                </div>
            </div>
        </div>
        <div class="col-6 row items-center img-con">
            <img class="ml-100p" src="https://tf.quomodosoft.com/appie/wp-content/uploads/2022/05/image.png" alt="">
            <div class= "ml-5f bg-circle bg-red w-500p h-500p br-50f">

            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .img-con{
        position: relative;
    }
    .bg-circle{ 
        position: absolute;
        z-index: -5;
    }

     
</style>