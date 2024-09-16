<script setup>
import HeadsetIntro from '../components/HeadsetIntro.vue'
import SurprisinsBenefits from '../components/SurprisinsBenefits.vue'
import VirtualReality from '../components/VirtualReality.vue'
import VrBenefits from '../components/VrBenefits.vue'
import VrBad from '../components/VrBad.vue'
import TheVirtual from '../components/TheVirtual.vue'
import KeyEducation from '../components/KeyEducation.vue'
import FooterSection from '../components/FooterSection.vue'
</script>

<template>
  <section class="headset-intro">
    <HeadsetIntro />
  </section>

  <section class="surprising-benefits">
    <SurprisinsBenefits />
  </section>

  <section class="virtual-reality">
    <VirtualReality />
  </section>

  <section class="vr-benefits">
    <VrBenefits />
  </section>

  <section class="vr-bad">
    <VrBad />
  </section>

  <section class="the-virtual">
    <TheVirtual />
  </section>

  <section class="key-education">
    <KeyEducation />
  </section>

  <footer class="footer-section">
    <FooterSection />
  </footer>
</template>
