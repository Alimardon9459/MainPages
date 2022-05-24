<template >
    <div class=" container row justify-center items-center text-h2 text-bold text-white">
        <div class="w-45f text-center" >
            The quintessence of rest
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>

    .container{
        width: 100%;
        height: 100vh;
        background-image: url(https://nuss.uxper.co/luxury-resort/wp-content/uploads/sites/6/2021/08/photo-1601701119533-fde20cecbf4e-16-1.jpeg);
        background-size: cover;
        background-repeat: no-repeat;
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