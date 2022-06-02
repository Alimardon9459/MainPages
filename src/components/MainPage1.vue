<template>
  <div class="row justify-center q-mt-xl ">
    <div  class="col-11 row justify-between ">
      <div class="col-4 row items-center">
        <div>
          <div class="text-h2 text-bold">
          <div>The Ultimate</div>
          <div class="row animation-group">
            <div class="text-for-animation-1">WordPress</div>
            <div class="text-for-animation-2">Online Store</div>
            <div class="text-for-animation-3">Creative</div>
            <div class="text-for-animation-4">Portfolio</div>
            <div class="text-for-animation-5">
              <div class="for-cursor"></div>
            </div>
          </div>
          <div>Website Builder</div>
          </div>
          <div class="text-h5 q-mt-lg">
            Trusted by beginners, marketers & professionals; Built with usability and performance in mind.
          </div>
          <div class="q-mt-xl">
            <q-btn to="/biblo" class="bg-black text-white q-pa-md " size="16px">Start Building <q-icon class="q-ml-md" name="east" /></q-btn>
          </div>
          <div class="q-mt-lg">
            <q-img width="100%" height="9px" src="https://avada.theme-fusion.com/wp-content/uploads/2021/06/small-separator.png" />
          </div>
          <div class="row q-mt-lg">
            <div>
              <div class="text-h4 text-bold">800k+</div>
              <div class="rating-text" >People Trust Avada</div>
            </div>
            <div class="q-ml-lg">
              <div class="text-h4 text-bold">24k+</div>
              <div class="rating-text" >Average 5-Star Reviews</div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-7">
        <q-img width="100%" src="https://avada.theme-fusion.com/wp-content/uploads/2021/07/home-hero-20@2x.jpg" />
      </div>
    </div>
  </div>
</template>

<style scoped>
  .rating-text{
    font-size: 16px;
  }
  .animation-group{
    position: relative;
  }
  .text-for-animation-1{
    height: 60px;
    animation-name: example1;
    animation-duration:15s;
    animation-iteration-count: infinite;
  }
  .text-for-animation-2{
    height: 60px;
    animation-name: example2;
    animation-duration:15s;
    animation-iteration-count: infinite;
  }
  .text-for-animation-3{
    height: 60px;
    animation-name: example3;
    animation-duration:15s;
    animation-iteration-count: infinite;
  }
  .text-for-animation-4{
    height: 60px;
    animation-name: example4;
    animation-duration:15s;
    animation-iteration-count: infinite;
  }
  .text-for-animation-5{
    position: absolute;
    background: rgb(255, 255, 255);
    height: 60px;
    width: 330px;
    animation-name: example5;
    animation-duration:15s;
    animation-iteration-count: infinite;

  }
  .for-cursor{
    width: 3px;
    height: 60px;
    background: #000;
  }

  @keyframes example1 {
    0%{
        opacity: 0;
        width: 0px;
    }
    1%{
        opacity: 1;
        width: auto;
    }
    24%{
        opacity: 1;
        width: auto;
    }
    25%{
        opacity: 0;
        width: 0px;
    }
    100%{
        opacity: 0;
        width: 0px;
    }

  }
  @keyframes example2 {
    0%{
        opacity: 0;
        width: 0px;
    }
    25%{
        opacity: 0;
        width: 0px;
    }
    26%{
        opacity: 0;
        width: auto;
    }
    27%{
      opacity: 1;
    }
    49%{
        opacity: 1;
        width: auto;
    }
    50%{
      opacity: 0;
    }
    51%{
        opacity: 0;
        width: 0px;
    }
    100%{
        opacity: 0;
        width: 0px;
    }
  }
  @keyframes example3 {
    0%{
        opacity: 0;
        width: 0px;
    }
    50%{
        opacity: 0;
        width: 0px;
    }
    51%{
        opacity: 1;
        width: auto;
    }
    74%{
        opacity: 1;
        width: auto;
    }
    75%{
        opacity: 0;
        width: 0px;
    }
    100%{
        opacity: 0;
        width: 0px;
    }
  }
  @keyframes example4 {
    0%{
        opacity: 0;
        width: 0px;
    }
    75%{
        opacity: 0;
        width: 0px;
    }
    76%{
        opacity: 1;
        width: auto;
    }
    99%{
        opacity: 1;
        width: auto;
    }
    100%{
        opacity: 0;
        width: 0px;
    }
  }
  @keyframes example5{
    0%{
      left: 0;
    }
    5%{
      left: 300px;
      width: 5px;
    }
    19%{
      left: 300px;
      width: 5px;
    }
    25%{
      left: 0px;
      width: 330px;
    }
    26%{
      left: 0;
      width: 330px;
    }
    31%{
      left: 330px;
      width: 5px;
    }
    44%{
      left: 330px;
      width: 5px;
    }
    50%{
        left: 0px;
        width: 330px;
    }
    51%{
      left: 0;
      width: 330px;
    }
    56%{
      left: 230px;
      width: 5px;
    }
    69%{
      left: 230px;
      width: 5px;
    }
    75%{
      left: 0px;
      width: 330px;
    }
    76%{
      left: 0;
      width: 330px;
    }
    81%{
      left: 250px;
      width: 5px;
    }
    95%{
      left: 250px;
      width: 5px;
    }
    100%{
      left: 0px;
      width: 330px;
    }

  }
</style>
