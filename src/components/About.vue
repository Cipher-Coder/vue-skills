<template>
  <div class="about">
    <h1>Hello {{ their_name }}, this is an About Page</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod timpor invididunt</p>
  </div>
</template>


<script>
export default {
  name: "Skills",
  data() {
    return {
      their_name: this.$route.params.name
    };
  }
};
</script>
