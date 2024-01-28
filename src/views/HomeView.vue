<script setup>
import ComputerImage from '@/assets/img/computer.svg';
import mobileusing from '@/assets/img/mobileusing.svg';
import meta from '@/assets/img/meta.svg';
import trabine from '@/assets/img/trabine.svg';
import NavBar from '@/components/NavBar.vue';
import Header from '@/components/Header.vue';
import VideoComp from '@/components/VideoComp.vue';
import ProjectComp from '@/components/ProjectComp.vue'
import ExpertieseRed from '@/components/ExpertieseRed.vue';
import WebDevelopment from '@/components/WebDevelopment.vue';
import NetroTeam from '@/components/NetroTeam.vue';
import AboutSection from '@/components/AboutSection.vue';
import ResponseSection from '@/components/ResponseSection.vue';
import FooterSection from '@/components/FooterSection.vue';
</script>

<template>
  <main class="">
    <NavBar />
    <Header />
    <VideoComp />
    <ProjectComp />
    <ExpertieseRed />
    <WebDevelopment 
                  :computerImage="ComputerImage"
                  number="01"
                  filedTitle="Developpement"
                  filedSubTitle="Web"
                  paragraph_one="Web Development"
                  paragraph_two="Frontend Development"
                  paragraph_three="Backend Development"
                  paragraph_four="Product Analytics"
                  paragraph_five="Technical Writing &amp; QA"
                  button_text="Voir les projets"
             />
    <WebDevelopment 
                  :computerImage="mobileusing"
                  number="02"
                  filedTitle="Application"
                  filedSubTitle="Mobile"
                  paragraph_one="iOS Development"
                  paragraph_two="Android Development"
                  paragraph_three="Backend Development"
                  paragraph_four="Product Analytics"
                  paragraph_five="Technical Writing &amp; QA"
                  class="-mt-3"
             />
    <WebDevelopment 
                  :computerImage="meta"
                  number="03"
                  filedTitle="Intelligence"
                  filedSubTitle="Artificielle"
                  paragraph_one="Résoudre des problèmes"
                  paragraph_two="D’accomplir des tâches multiples"
                  paragraph_three="Booster le Big Data"
                  paragraph_four="Exécuter des tâches plus complexes"
                  class="-mt-3"
             />
    <WebDevelopment 
                  :computerImage="trabine"
                  number="04"
                  filedTitle="UI/UX"
                  filedSubTitle="Designer"
                  paragraph_one="Art Direction"
                  paragraph_two="UI/UX Design"
                  paragraph_three="Motion Design"
                  paragraph_four="3D Design"
                  class="-mt-3"
             />
    <NetroTeam />
    <AboutSection />
    <ResponseSection />
    <FooterSection />
  </main>
</template>
