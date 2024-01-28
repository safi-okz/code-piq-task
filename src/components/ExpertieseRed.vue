<script setup>
import redBack from '@/assets/img/redBack.svg';
</script>

<template>
    <div>
        <img :src="redBack" alt="">
        <div class="bg-[#100021] py-3">
            <marquee behavior="scroll" direction="right">
            <h1 class="font-bold text-6xl uppercase expertiese_animation">
                <span class="expertiese_text">Expertises </span>
                <span class="text-white">Expertises </span>
            </h1>
        </marquee>
        </div>
    </div>
</template>

<style scoped>
.expertiese_text {
    -webkit-text-stroke: 1px #fff;
}

.expertiese_animation {
    animation: slideIn 2s infinite ease-out;
}
</style>