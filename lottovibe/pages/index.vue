<script setup lang="ts">

useHead({
  title: "Treatly",
  meta: [{ name: "description", content: "Win yourself something special" }],
});

definePageMeta({
  layout: "landing-pages",
});</script>
<template>
  <NavbarBlack />
  <HomeOneBanner />
  <HomeOneLotteryService />
  <HomeOneLuxuryV1 />
  <HomeOneHowItSectionV1 />
  <HomeOneWinLotterySection />
  <HomeOneCarCategorySection />
  <HomeOneTestimonialSection />
  <HomeOneCallToSection />
  <HomeOneBlogSection />
  <Faq :bg-color="true" />
  <HomeOneSmartphoneSection />
  <HomeOneSponsorSection />
  <HomeOneFooter />
</template>

<style scoped></style>
