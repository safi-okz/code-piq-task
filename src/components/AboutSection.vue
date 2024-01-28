<script setup>
import LogoLeaf from '@/assets/img/Logo-leaf.png'
</script>

<template>
    <div class="about_section pb-10 pt-[5rem] border-dashed border-t-[#000] border-t-[1px]">
        <div class="flex md:flex-nowrap sm:flex-wrap flex-wrap items-center gap-x-8 pt-[5rem] mx-[10rem]">
            <div>
                <img :src="LogoLeaf" class="!w-[65.9928rem] h-[6.5322rem]" alt="">
            </div>
            <div>
                <div class="border-b-[.8px] border-b-black w-[15rem]"></div>
            </div>
            <div>
                <p class="leading-[1.1rem]">
                    Les projets de l’agence web ne se limitent pas qu’à ceux de nos clients. Que ce soit au niveau de l’environnement, du bien commun ainsi que du bien-être de nos collaborateurs, chaque année, AjiCreative essaie de se surpasser !
                </p>
            </div>
        </div>
    </div>
</template>

<style scoped>
.about_section {
    background: url('../assets/img/header.svg');
    background-position: top;
    background-repeat: no-repeat;
}
</style>