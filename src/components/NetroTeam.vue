<script setup>
import Hand from '@/assets/img/hand.png'
import CEO from '@/assets/img/ceo.png';
import speaker from '@/assets/img/speaker.png'
import moflarGirl from '@/assets/img/moflarGirl.png';
import kingGirl from '@/assets/img/kingGirl.png'
import headPhoneMan from '@/assets/img/headPhoneMan.png';
import mobileUser from '@/assets/img/mobileUser.png';
import speakingMan from '@/assets/img/speakingMan.png';
import lughingGirl from '@/assets/img/lughingGirl.png';
import worryMan from '@/assets/img/worryMan.png';
import pinkBox from '@/assets/img/pinkbox.svg';
import darkPink from '@/assets/img/darkPink.svg';
import greenBox from '@/assets/img/greenBox.svg';
import yellowBox from '@/assets/img/yellowBox.svg';
import darkBlue from '@/assets/img/darkBlue.svg';
import mixGreenBox from '@/assets/img/mixGreenBox.svg';
import skyBlue from '@/assets/img/skyBlue.svg';
import arrowLeft from '@/assets/img/arrow-circle-left.svg';
import arrowRight from '@/assets/img/arrow-circle-right.svg';
</script>

<template>
    <div class="team_back p-5">
        <div class="flex justify-center items-center ">
        <h1 class="text-[6rem] font-[600]">
            <span class="text-[#4606F0]">Notre </span>
            <span class="text-[#CDCFD7]">Team</span>
        </h1>
        <div>
            <img :src="Hand" class="mt-2 ms-4 " alt="Hand image">
        </div>
        </div>
        <div class="relative">
            <img :src="CEO" class="w-[38rem] absolute left-[20%] mt-10" alt="Ceo image">
            <img :src="speaker" class="absolute top-[26rem] w-[5rem] left-[50%]" alt="Speaker button">
            <img :src="moflarGirl" class="w-[8rem] absolute top-[4rem] left-[25%]" alt="Girl lughing with red moflar">
            <div class="absolute top-0 left-[17%]">
                <div class="relative">
                    <img :src="pinkBox" alt="pink box">
                    <p class="absolute top-[50%] left-9">Oceane</p>
                </div>
            </div>
            <img :src="kingGirl" class="w-[8rem] absolute top-[9rem] left-[9%]" alt="King Girl">
            <img :src="headPhoneMan" class="w-[8rem] absolute top-[24rem] left-[26%]" alt="King Girl">
            <div class="absolute top-[21.5rem] left-[6%]">
                <div class="relative">
                    <img :src="darkPink" alt="pink box">
                    <p class="absolute top-[50%] left-6">Anissa</p>
                </div>
            </div>
            <div class="absolute top-[27.5rem] left-[40%]">
                <div class="relative">
                    <img :src="yellowBox" alt="yellow box">
                    <p class="absolute top-[50%] left-9">Sylvain</p>
                </div>
            </div>
            <div class="absolute top-[34rem] left-[29%]">
                <div class="relative">
                    <img :src="greenBox" alt="green box">
                    <p class="absolute top-[50%] left-10">Tiago</p>
                </div>
            </div>
            <div class="uppercase text-center absolute left-[42%] top-[32rem]">
                <p class="text-[#EAEAEA] text-[0.7183rem]">design</p>
                <p class="text-[#C8C8C8] text-[0.8969rem] -my-2">UI/UX DESIGNER</p>
                <p class="text-[#828282] text-[1rem] -my-3">développement web</p>
                <h3 class="text-[#000] text-[1.8rem] -mt-2">application mobile</h3>
                <h3 class="text-[#828282] text-[1rem] -mt-3">Intelligence Artificielle</h3>
                <p class="text-[#C8C8C8] text-[0.8558rem] -mt-2">Branding</p>
                <p class="text-[#EAEAEA] text-[0.7434rem] -mt-2">aji group</p>
            </div>
            <div class="absolute top-[0] right-[27%]">
                <div class="relative">
                    <img :src="darkPink" alt="pink box">
                    <p class="absolute top-[50%] left-8">Theo</p>
                </div>
            </div>
            <div class="absolute top-[9rem] right-[1%]">
                <div class="relative">
                    <img :src="darkBlue" alt="pink box">
                    <p class="absolute top-[50%] left-9 text-white">Youssef</p>
                </div>
            </div>
            <img :src="mobileUser" class="w-[12rem] top-[2.2rem] absolute right-[12%]" alt="Man using mobile">
            <img :src="speakingMan" class="w-[9rem] top-[15rem] absolute right-[5%]" alt="Speaking Man">
            <img :src="lughingGirl" class="w-[11rem] top-[24rem] absolute right-[17%]" alt="Lughing Girl">
            <img :src="worryMan" class="w-[11rem] top-[28rem] absolute right-0" alt="Worry Man">
            <div class="absolute top-[24rem] right-[3%]">
                <div class="relative">
                    <img :src="mixGreenBox" alt="pink box">
                    <p class="absolute top-[50%] left-9">Adil</p>
                </div>
            </div>
            <div class="absolute top-[34rem] right-[22%]">
                <div class="relative">
                    <img :src="skyBlue" alt="pink box">
                    <p class="absolute top-[50%] left-9">Eulalie</p>
                </div>
            </div>
        </div>
    </div>
            <div class="flex justify-center -mt-[7rem]">
                <button class="border-0">
                    <img :src="arrowLeft" class="w-[3rem]" alt="">
                </button>
                <button class="border-0">
                    <img :src="arrowRight" class="w-[3rem]" alt="">
                </button>
            </div>
</template>

<style scoped>
.team_back {
    background: url('../assets/img/Map.svg') no-repeat center center / cover;
    height: 57rem;
}
</style>