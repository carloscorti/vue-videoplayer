<template>
  <div class="video-container">
    <vue-plyr ref="plyr">
      <div data-plyr-provider="vimeo" :data-plyr-embed-id="videoid"></div>
    </vue-plyr>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    videoid: Number,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "./videooverlaz.scss";
</style>
