<template>
  <div class="container">
      <Navbar />
  </div>
</template>

<script>
import Navbar from "~/components/Navbar.vue";
import Footer from "~/components/Footer.vue"
export default {
  components: {
    Navbar
  }
};
</script>

<style>


body {
  box-sizing: inherit;
}

*,
*:before,
*:after {
  margin:0; 
  padding: 0; 
  box-sizing: border-box;
}
</style>
