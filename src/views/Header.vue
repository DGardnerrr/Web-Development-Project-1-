<template>
  <header class="header">
    <img alt="logo" src="http://placekitten.com/300/150" />
    <ol class="nav">
      <li class="nav-item">Features</li>
      <li class="nav-item">About</li>
      <li class="nav-item">Testimonial</li>
      <li class="nav-item">Download</li>
      <li class="nav-item">Contact</li>
    </ol>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header {
  display: flex;
  justify-content: space-between;
}
.nav-item {
  display: inline;
  padding: 10px 15px;
}
</style>
