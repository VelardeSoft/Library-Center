<script>
import { defineComponent } from 'vue';
export default defineComponent({
  name: 'TheFooter',
});
</script>

<template>
  <footer class="thefooter">
    <p>Library Center © 2024</p>
  </footer>
</template>

<style>
.thefooter {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px;
  background-color: #4a7ad2;
  left: 0;
  bottom: 0;
  width: 100%;
  position: fixed;
  z-index: 1000;
}
p {
  color: white;
  font-size: 15px;
  margin-left: 600px;
}
</style>