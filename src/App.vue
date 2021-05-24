<template>
  <div id="app">
    <VideoOverlay :videoid="143418951" />
    <br />
    <br />
    <VideoOverlay :videoid="359401845" />
    <br />
    <br />
    <VideoOverlay :videoid="248085793" />
    <br />
    <br />
    <VideoOverlay :videoid="357788702" />
  </div>
</template>

<script>
import VideoOverlay from "./components/VideoOverlay.vue";

export default {
  name: "App",
  components: {
    VideoOverlay,
  },
};
</script>

<style>
* {
  box-sizing: border-box !important;
  margin: 0;
  padding: 0;
}
#app {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  max-width: 100vw;
  overflow: hidden;
}
br {
  display: block;
  height: 20px;
  /* width: 100vw; */
}
</style>
