<script setup>
import faceBookIcon from '@/assets/img/gg_facebook.svg';
import instagramIcon from '@/assets/img/uil_instagram.svg';
import linkedInIcon from '@/assets/img/mdi_linkedin.svg';
import youtubeIcon from '@/assets/img/mdi_youtube.svg';
import logo_icon from '@/assets/img/logo-icon.png';
</script>

<template>
    <div class="footer_back -mt-[5rem] overflow-hidden pb-12">
        <img src="../assets/img/footer.svg" class="" alt="">
        <div class="grid grid-lg-cols-2 md:grid-cols-2 sm:grid-cols-1 px-[5rem]">
            <div>
                <div class="flex gap-x-[3rem]">
                    <a href="#" class="decoration-0">
                        <img :src="faceBookIcon" class="w-[1.5rem]" alt="Facebook icon">
                    </a>
                    <a href="#" class="decoration-0">
                        <img :src="instagramIcon" class="w-[1.5rem]" alt="Facebook icon">
                    </a>
                    <a href="#" class="decoration-0">
                        <img :src="linkedInIcon" class="w-[1.5rem]" alt="Facebook icon">
                    </a>
                    <a href="#" class="decoration-0">
                        <img :src="youtubeIcon" class="w-[1.5rem]" alt="Facebook icon">
                    </a>
                </div>
            <div>
                <p class=" text-[1.2rem]">© 2023 All Right Reserved | AjiCreative</p>
            </div>
            <div class="grid grid-cols-2 -mt-1">
                <div>
                    <p class="font-[200] text-[1.2rem]">Mentions légales</p>
                    <p class="font-[200] text-[1.2rem] -mt-1">Politique de confidentialité</p>
                </div>
                <div>
                    <p class="font-[200] text-[1.2rem]">Politique de cookies</p>
                    <p class="font-[200] text-[1.2rem] -mt-1">CGV</p>
                </div>
            </div>
            </div>
            <div>
                <img :src="logo_icon" class="mt-9" alt="">
            </div>
        </div>
            
    </div>
</template>