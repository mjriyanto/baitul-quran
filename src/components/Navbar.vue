<script setup></script>

<template>
  <nav class="navbar">
    <div class="navbar__title">BAITUL QURAN ATTIBYAN</div>
    <div class="navbar__menu">
      <div class="navbar__item">Beranda</div>
      <div class="navbar__item">Tentang Kami</div>
      <div class="navbar__item">Berita</div>
      <div class="navbar__item">Donasi</div>
      <div class="navbar__item">Kontak</div>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 24px;
  max-width: 900px;
  margin: auto;
  color: #ffffff;
  z-index: 1;

  &__title {
    font-family: 'PlusJakartaSans-Bold', sans-serif;
  }

  &__menu {
    display: flex;
    column-gap: 32px;
  }

  &__item {
    border-bottom: 2px solid transparent;
    &:hover {
      cursor: pointer;
      border-bottom: 2px solid #ffffff;
    }
  }
}
</style>
