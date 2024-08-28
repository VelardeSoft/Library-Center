<script>
import { defineComponent } from 'vue';
export default defineComponent({
  name: 'AppHeader',
});
</script>

<template>
  <header class="app-header">
    <img src="../assets/LogoUPC.png" alt="Logo" class="logo" />
    <p>Library Center</p>
  </header>
</template>

<style>
.app-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
  background-color: #4a7ad2;
  left: 0;
  top: 0;
  width: 100%;
  position: fixed;
  z-index: 1000;
}
.logo {
  height: 50px;
}
p {
  font-size: 20px;
  margin-right: 80px;
}
</style>