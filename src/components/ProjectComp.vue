<template>
    <div class="bg-[#4606F0] px-12 pt-[8rem] pb-[5rem]">
        <div class="text-center">
            <p class="text-[2.2rem] text-white font-[600]">AJI Creative</p>
            <h1 class="font-[600] text-[6.5rem] uppercase heading_img">Nos Projects</h1>
        </div>
        <!-- Project Row 1 Start -->
        <div class="grid md:grid-cols-2 sm:grid-cols-1 gap-x-8 mt-10">
            <div>
                <div class="flex flex-wrap md:justify-center ms:justify-left items-center">
                        <h4 class="text-[5.5rem] text-white">600</h4>
                    <div class="ms-2">
                        <h1 class="text-[1.6rem] uppercase text-[#00D2AE]">
                            <span class="block -mb-1 mt-1">projets</span>
                            <span class="">réalisés</span>                                   
                        </h1>
                    </div>
                </div>
            </div>
            <div>
                <div class="flex items-center">
                        <h4 class="text-[5.5rem] text-white">56</h4>
                    <div class="ms-2">
                        <h1 class="text-[1.6rem] uppercase text-[#00D2AE]">
                            <span class="block -mb-1 mt-1">collaborateurs</span>
                            <span class="">passionnés</span>                                   
                        </h1>
                    </div>
                </div>
            </div>
        </div>
         <!-- Project Row 1 End -->
         <!-- Project Row 2 Start -->
         <div class="grid md:grid-cols-2 sm:grid-cols-1 md:gap-x-8 sm:gap-x-0 -mt-5">
            <div>
                <div class="flex md:justify-center ms:justify-left items-center">
                        <h4 class="text-[5.5rem] text-white">100&percnt;</h4>
                    <div class="ms-2">
                        <h1 class="text-[1.6rem] uppercase text-[#00D2AE]">
                            <span class="block -mb-1 mt-1">clients</span>
                            <span class="">satisfaits</span>                                   
                        </h1>
                    </div>
                </div>
            </div>
            <div>
                <div class="flex items-center">
                        <h4 class="text-[5.5rem] text-white">14</h4>
                    <div class="ms-2">
                        <h1 class="text-[1.6rem] uppercase text-[#00D2AE]">
                            <span class="block -mb-1 mt-1">années au</span>
                            <span class="">service de nos clients</span>                                   
                        </h1>
                    </div>
                </div>
            </div>
        </div>
         <!-- Project Row 2 End -->
    </div>
</template>

<style scoped>
.heading_img {
    background-image: url('../assets/img/nose.svg');
    color: transparent;
    -webkit-background-clip: text;
    background-clip: text;
    background-repeat: repeat-x;
    background-size: contain;
}
</style>