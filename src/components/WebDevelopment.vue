<script setup>

const props = defineProps({
    computerImage: String,
    number: String,
    filedTitle: String,
    filedSubTitle: String,
    paragraph_one: String,
    paragraph_two: String,
    paragraph_three: String,
    paragraph_four: String,
    paragraph_five: String
});
</script>

<template>
    <div class="web_back px-12 pb-12 pt-12" :style="{'background-image': `url( ${computerImage} )`}">
        <div class="pt-[4rem]">
            <div>
                <h1 class="text-[4rem] font-semibold text-white tracking-widest mb-0">{{ number }}</h1>
                <h1 class="text-[3rem] font-semibold text-white capitalize -mt-7">{{ filedTitle }}</h1>
                <h1 class="text-[3rem] font-semibold text-[#FFD644] -mt-5">{{ filedSubTitle }}</h1>
                <div>
                    <div class="text-white border-l-[1px] border-l-white ms-[5.5rem] py-4 mt-2">
                        <p class="ms-7">{{ paragraph_one }}</p>
                        <p class="-mt-1 ms-7">{{ paragraph_two }}</p> 
                        <p class="-mt-1 ms-7">{{ paragraph_three }}</p> 
                        <p class="-mt-1 ms-7">{{ paragraph_four }}</p> 
                        <p class="-mt-1 ms-7">{{ paragraph_five }}</p>
                    </div>
                </div>
                <button class="text-[1.2rem] font-semibold text-white mt-6 rounded-full border-[1px] border-white py-2 px-5 mb-10">Voir les projets</button>
            </div>
        </div>
    </div>
</template>

<style scoped>
.web_back {
    /* background-image: url('../assets/img/computer.svg'); */
    background-repeat: no-repeat;
    background-size: cover;
}
</style>