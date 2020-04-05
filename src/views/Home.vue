<template>
  <div class="home">
    <HeaderNaoki />
    <CarouselNaoki />
    <WomanNaoki />
    <InstaNaoki />
    <PartnerLogoNaoki />
    <FooterNaoki />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderNaoki from "@/components/HeaderNaoki.vue";
import CarouselNaoki from "@/components/CarouselNaoki.vue";
import WomanNaoki from "@/components/WomanNaoki.vue";
import InstaNaoki from "@/components/InstaNaoki.vue";
import PartnerLogoNaoki from "@/components/PartnerLogoNaoki.vue";
import FooterNaoki from "@/components/FooterNaoki.vue";

export default {
  name: "Home",
  components: {
    HeaderNaoki,
    CarouselNaoki,
    WomanNaoki,
    InstaNaoki,
    PartnerLogoNaoki,
    FooterNaoki
  }
};
</script>
