<script setup>
import { onMounted, ref } from 'vue';
import ajVideo from '@/assets/img/ajvVideo.mp4';

const videoElement = ref(null);

onMounted(() => {
    window.addEventListener('scroll', () => {
        const scale = 1 + window.scrollY / 1000;
        videoElement.value.style.transform = `scale(${scale})`;
    });
});
</script>

<template>
    <div class="video-container relative overflow-hidden">
        <video :src="ajVideo" autoplay ref="videoElement" class="video transition-transform duration-300 ease-out"></video>
        <h1 class="title text-[17rem] text-[#071952da] font-semibold absolute top-[22%] left-[1%] ">
            AJI VIDEO 
        </h1>
    </div>
</template>