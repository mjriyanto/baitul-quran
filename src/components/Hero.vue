<script setup></script>

<template>
  <div class="hero">
    <h3 class="hero__title">
      Selamat Datang di <br />
      Situs Web Baitul Quran Attibyan
    </h3>
    <span class="hero__subtitle">
      Bertaqwa, Berakhlak Mulia, Berprestasi, Berwawasan Lingkungan dan Global
      yang berpijak pada Budaya Bangsa
    </span>
    <button class="hero__cta">Donasi sekarang</button>
  </div>
</template>

<style lang="scss" scoped>
.hero {
  height: 500px;
  width: 100%;
  color: #ffffff;
  max-width: 900px;
  margin: auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  row-gap: 40px;
  text-align: center;

  &__title {
    font-family: 'PlusJakartaSans-Bold', sans-serif;
    font-size: 48px;
    line-height: 68px;
  }

  &__subtitle {
    max-width: 75%;
    margin: 0 auto;
    font-size: 16px;
    line-height: 24px;
  }

  &__cta {
    margin: 0 auto;
    padding: 12px 18px;
    background-color: transparent;
    color: #ffffff;
    border: 1px solid #ffffff;
    outline: none;
    border-radius: 28px;
    cursor: pointer;
    font-size: 20px;

    &:hover {
      background-color: #ffffff;
      color: #095a4ae6;
    }
  }
}
</style>
