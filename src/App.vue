<script setup>
import Navbar from '@/components/Navbar.vue';
import Hero from '@/components/Hero.vue';
</script>

<template>
  <section class="container-top">
    <div class="container-top__content">
      <Navbar />
      <Hero />
    </div>
  </section>
</template>

<style lang="scss">
.container-top {
  position: relative;
  width: 100%;
  height: 80vh;

  &:before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border-radius: 0 0 50% 50%/0 0 20%;
    background-image: url('@/assets/images/background-hero.jpg');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    box-shadow: inset 0 0 0 500px rgba(9, 90, 74, 0.9);
  }

  &__content {
    position: relative;
    z-index: 1;
  }
}
</style>
