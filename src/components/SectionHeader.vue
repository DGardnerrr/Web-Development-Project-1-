<template>
  <div class="section-header">
    <h2>
      {{ headline }}
    </h2>
    <p>
      {{ description }}
    </p>
  </div>
</template>

<script>
export default {
  name: "SectionHeader",
  props: { headline: String, description: String },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.section-header {
  text-align: center;
}
</style>
