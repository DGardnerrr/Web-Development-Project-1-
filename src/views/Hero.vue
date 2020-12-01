<template>
  <section class="hero">
    <div class="overlay">
      <h1>
        This Will Be The Headline
      </h1>
      <p>
        insert paragraph here
      </p>
    </div>
    <video class="video" autoplay muted loop playsinline>
      <source
        type="video/mp4"
        src="http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/Sintel.mp4"
      />
      The browser does not support the video tag
    </video>
  </section>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.overlay {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}
.video {
  width: 100%;
  height: auto;
}
.hero {
  position: relative;
}
</style>
