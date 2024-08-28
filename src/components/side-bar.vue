<script>
import { defineComponent } from 'vue';
export default defineComponent({
  name: 'SideBar',
});
</script>

<template>
  <aside class="side-bar">
    <nav>
      <ul>
        <li>Books</li>
        <li>Authors</li>
        <li>Genres</li>
      </ul>
    </nav>
  </aside>
</template>

<style scoped>
.side-bar {
  width: 300px;
  background-color: #513c86;
  padding: 10px;
  position: fixed;
  top: 60px;
  left: 0;
  height: 83%;
  border-radius: 20px;
}
nav ul {
  list-style-type: none;
  padding: 0;
}
nav li {
  margin: 15px 0;
  color: white;
}
</style>