<template>
  <section>
    <media-player
      v-for="project in projecten"
      :key="project.id"
      :link="project.link"
      class="video"
    ></media-player>
  </section>
</template>

<script>
import PROJECTEN from '../static/projecten.js'
import MediaPlayer from './components/MediaPlayer.vue'

export default {
  name: 'IndexPage',
  components: {
    MediaPlayer,
  },
  data() {
    return {
      projecten: PROJECTEN,
    }
  },
  onLoad() {
    console.log(this.projecten)
  },
}
</script>

<style scoped>
.video {
  border-radius: 1rem;
  box-shadow: 0 0.2rem 2rem rgba(0, 0, 0, 0.26);
  padding: 1.5rem;
  margin: 6rem auto;
  max-width: 70%;
}
</style>
