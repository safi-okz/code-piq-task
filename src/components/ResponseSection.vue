<script setup>
import plusIcon from '@/assets/img/plusIcon.svg'
</script>

<template>
    <div class="response_back mb-8">
        <div class="flex flex-wrap gap-x-3 items-end h-[460px]">
            <div>
                <h1 class="font-semibold text-white ps-1 text-[2.5rem]">Humain</h1>
            </div>
            <div>
                <h1 class="font-semibold text-white text-[2.5rem] ps-3">
                    <span class="block">Eco</span> 
                    <span class="block -my-4">Respon</span> 
                    <span class="block">sable</span>                                       
                </h1>
            </div>
            <div class="ms-5">
                <h1 class="font-semibold text-[#FFD644] text-[2.5rem]">Nouvelles</h1>
                <p class="text-white mt-1">Les projets de l’agence web ne se limitent pas qu’à ceux de nos clients. </p>
                <p class="text-white -mt-2">Que ce soit au niveau de l’environnement, du bien commun. </p>
            </div>
            
        </div>
        <div class="flex mt-9 gap-[8rem]">
        <div class="">
            <img :src="plusIcon" class="w-[2rem] ms-[4rem]" alt="">
        </div>
        <div>
            <img :src="plusIcon" class="w-[2rem]" alt="">
        </div>
        <div class="flex items-center">
            <img :src="plusIcon" class="w-[2rem]" alt="">
            <h4 class="font-bold ms-2">Savoir plus</h4>
        </div>
    </div>
    </div>
</template>

<style scoped>
.response_back {
    background-image: url('../assets/img/responseImage.svg');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    height: 550px;
}
</style>