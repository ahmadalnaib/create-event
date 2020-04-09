<template>
  <div id="app">
    <Navbar />
    <div class="container">
      <router-view />
    </div>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';
export default {
  components: {
    Navbar,
  },
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
body {
  background: #333;
  line-height: 1.7;
  font-size: 1rem;
  text-align: center;
}

.container {
  max-width: 1100px;
  margin: auto;
  overflow: hidden;
}

ul {
  list-style: none;
}
a {
  text-decoration: none;
  color: green;
}
</style>
