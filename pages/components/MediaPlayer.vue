<template>
  <div>
    <video-player :src="link" />
  </div>
</template>

<script>
import VideoPlayer from 'nuxt-video-player'

require('nuxt-video-player/src/assets/css/main.css')
export default {
  components: {
    VideoPlayer,
  },
  props: {
    title: {
      type: String,
      default: null,
    },
    link: {
      type: String,
      default: null,
    },
  },
}
</script>
