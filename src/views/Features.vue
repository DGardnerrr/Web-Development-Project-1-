<template>
  <section class="features">
    <SectionHeader headline="Main Features" description="insert description" />
    <div class="features__container">
      <Feature headline="Feature" description="insert description" />
      <Feature headline="Feature" description="insert description" />
      <Feature headline="Feature" description="insert description" />
    </div>
  </section>
</template>

<script>
import SectionHeader from "@/components/SectionHeader.vue";
import Feature from "@/components/Feature.vue";
export default {
  name: "Features",
  components: { SectionHeader, Feature },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.features {
  &__container {
    display: flex;
    justify-content: space-between;
  }
}
</style>
