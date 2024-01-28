<script setup>
import { ref, onMounted, nextTick } from 'vue';
import ajVideo from '@/assets/img/ajvVideo.mp4';

const videoElement = ref(null);

onMounted(() => {
  window.addEventListener('scroll', () => {
        nextTick(() => {
            if (videoElement.value) {
                const scale = 1 + window.scrollY / 1000;
                videoElement.value.style.transform = `scale(${scale})`;
            }
        });
    });
});
</script>

<template>
    <div class="headr_background px-5 pb-[10rem]">
        <div class="flex flex-grow flex-wrap items-center pt-[9rem] px-5 ">
            <div class="w-100 text-center uppercase ps-8">
                <h6 class="text-[1.2rem] text-[#F9F9F9] font-[500]">Desing</h6>
                <h6 class="text-[1.2rem] text-[#F9F9F9] font-[500] -mt-2">UI/UX DESIGNER</h6>
                <h6 class="text-[1.7rem] font-[600] text-[#38efad47] -mt-3">développement web</h6>
                <h4 class="header_app_heading text-[50px] font-semibold my-0 py-0 text-transparent -mt-6">APPLICATION MOBILE</h4>
                <h4 class="text-transparent header_app_two text-[30px] z-[30] font-[500] -mt-5">INTELLIGENCE ARTIFICIELLE</h4>
                <h4 class="text-[1rem] font-[600] text-[#D7FFF0] -mt-2">Branding</h4>
                <h6 class="text-[1rem] font-[600] -mt-2">aji group</h6>
            </div>
            <div class="flex-grow w-100 flex justify-end pe-10">
                <div class="relative !overflow-hidden w-[32rem] !h-[20rem]">
                    <video :src="ajVideo" ref="videoElement" autoplay class="w-[32rem] !h-[22rem] overflow-hidden transition-transform duration-300 ease-out"></video>
                    <h1 class="text-[6.8rem] text-[#071952da] font-semibold absolute top-[30%] left-[2%]">AJI VIDEO</h1>
                </div>
            </div>
        </div>
        <div href="#" class="circle green"></div>
        <div href="#" class="circle pink"></div>
        <div href="#" class="circle blue"></div>
    </div>
</template>

<style scoped>
.headr_background {
    background-image: url('../assets/img/header.svg');
    background-size: cover;
    background-position: top;
    background-repeat: no-repeat;
    z-index: -2;
    position: relative;
    overflow: hidden;
}  

.header_app_heading {
-webkit-text-stroke: .5px black;
}

.header_app_two {
  -webkit-text-stroke: .5px #fff;
}

.circle {
  text-decoration: none;
  display: block;
  position: absolute;
  border-radius: 50%;
  z-index: -1;
}

.green {
  left: 0;
  top: 0;
  background-color: rgba(94, 224, 163, 0.3);
  width: 18rem;
  height: 18rem;
  filter: blur(10px);
  animation: moveGreen 12s linear infinite alternate-reverse;
}

.pink {
  left: 5%;
  top: 50%;
  background-color: rgba(232, 143, 201, 0.4);
  width: 15rem;
  height: 15rem;
  filter: blur(10px);
  animation: movePink 12s linear infinite alternate;
}

.blue {
  bottom: 0;
  right: 0;
  background-color: #6cffee6d;
  width: 11rem;
  height: 11rem;
  filter: blur(10px);
  animation: moveBlue 12s linear infinite alternate-reverse;
}

@keyframes moveGreen {
  0% {
    top: 0;
    left: 0;
  }

  20% {
    top: 0;
    left: 90%;
  }

  40% {
    top: 70%;
    left: 40%;
  }

  60% {
    top: 40%;
    left: 0;
  }

  80% {
    top: 40%;
    left: 80%;
  }

  100% {
    top: 0;
    left: 0;
  }
}

@keyframes movePink {
  0% {
    top: 0;
    right: 0;
  }

  20% {
    top: 0;
    left: 90%;
  }

  40% {
    top: 90%;
    left: 40%;
  }

  60% {
    top: 40%;
    left: 0;
  }

  80% {
    top: 40%;
    right: 40%;
  }

  80% {
    top: 0;
    right: 0;
  }
}

@keyframes moveBlue {
  0% {
    bottom: 0;
    right: 0;
  }

  20% {
    bottom: 40%;
    right: 50%;
  }

  40% {
    bottom: 40%;
    right: 0;
  }

  60% {
    bottom: 90%;
    right: 90%;
  }

  80% {
    bottom: 20%;
    right: 70%;
  }

  100% {
    bottom: 0;
    right: 0;
  }
}

</style>