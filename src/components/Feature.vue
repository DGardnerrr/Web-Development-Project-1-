<template>
  <div class="feature">
    <h3>
      {{ headline }}
    </h3>
    <p>
      {{ description }}
    </p>
  </div>
</template>

<script>
export default {
  name: "Feature",
  props: { headline: String, description: String },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.feature {
  position: relative;
  padding-left: 40px;
  &::before {
    left: -40px;
    position: absolute;
    content: "\2713";
    border: 1px solid black;
    border-radius: 50%;
    width: 30px;
    height: 30px;
    display: inline-block;
    text-align: center;
  }
}
</style>
