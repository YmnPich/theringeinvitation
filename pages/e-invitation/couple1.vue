<template>
  <div>
    <img src="/asset/thering-couple.jpg" style = "object-fit: contain;width: 200px;height: 200px;" alt="My Image" @click="showFullImage">
    <div v-if="showFullImage" :class="{ fullscreen: showFullImage }">
      <img src="/asset/thering-couple.jpg" style = "object-fit: contain;width: 200px;height: 200px;"alt="My Image" @click="hideFullImage">
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      showFullImage: false
    }
  },
  methods: {
    showFullImage() {
      this.showFullImage = true
    },
    hideFullImage() {
      this.showFullImage = false
    }
  }
}
</script>