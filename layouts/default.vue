<template>
  <div class="__wrap">
    <Header />
    <SideText />
    <Nuxt />
    <Footer />
  </div>
</template>

<script setup lang="ts">
import Header from "~/components/common/Header.vue";
import Footer from "~/components/common/Footer.vue";
import SideText from "~/components/common/SideText.vue";
</script>

<style lang="scss" scoped>
.__wrap {
  width: 100%;
  position: relative;
}
</style>
