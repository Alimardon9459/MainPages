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
            <q-btn class="bg-black text-white q-pa-md " size="16px">Start Building <q-icon class="q-ml-md" name="east" /></q-btn>
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
<script>
    const cursor=document.querySelector(".cursor")
    document.addEventListener("mousemove" ,(e)=>{
      let x = e.pageX;
      let y = e.pageY;
      cursor.style.top = y + "px";
      cursor.style.left = x + "px";
      cursor.style.display ="block";
    })

    document.addEventListener("mouseout" , ()=>{
      cursor.style.display="none";
    })
</script>

<style scoped>
      .container{
        position: fixed;
        width: 100%;
        z-index: 999;
        display: flex;
        justify-content: center;
        align-items: center;
      }
      .cursor{
        position: fixed ;
        z-index: 999;
        background: #2696e8;
        width: 20px;
        height: 20px;
        border-radius: 50%;
        pointer-events: none;
        animation: colors 5s infinite;
        box-shadow: 0  0  2px #2696e8, 0 0 60px #2696e8, 0 0 100px #2696e8 ;
        transform: translate(-50% , -50%);
        display: none;
        display:flex;
        justify-items: center;
        align-items: center;
      }
      @keyframes colors{
        0%{
          filter: hue-rotate(0deg);
        }
        100%{
          filter: hue-rotate(360deg);
        }
      }
      .cursor:before{
        content: "";
        position: absolute;
        background: #2696e8;
        opacity: 0.2;
        width: 50px;
        height: 50px;
        transform: translate(-30%,-30%);
        border-radius: 50%;
      }
      .in-cursor{
        border: 5px solid #2696e8;
        border-radius: 50%;
        opacity: 0;
        width: 0px;
        height: 0px;
        animation: colorss 0.5s infinite;

      }
      .in-cursor:hover{
        opacity: 1;

      }
      @keyframes colorss{
        0%{
          filter: hue-rotate(0deg);
        }
        100%{
          width: 100px;
          height: 100px;
          transform: translate(-40%,-40%);
          filter: hue-rotate(360deg);
        }
      }


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
