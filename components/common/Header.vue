<template>
  <div class="header-wrap">
    <div class="logo-container">Logo</div>
  </div>
</template>

<script lang="ts" setup></script>

<style lang="scss" scoped>
.header-wrap {
  position: fixed;
  z-index: 9;

  .logo-container {
    width: 60px;
    height: 60px;
    background-color: gray;

    margin: 60px 0 0 60px;
  }
}
</style>
