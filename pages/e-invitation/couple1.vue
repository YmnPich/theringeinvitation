<template>
  <div>
    <!-- Image Grid for thumbnails -->
    <div class="image-grid">
      <!-- <img
        v-for="(img, index) in images"
        :key="index"
        :src="img"
        @click="openModal(img)"
        class="thumbnail"
        alt="thumbnail"
      /> -->
      <!-- <img src="/asset/thering-couple.jpg" @click="openModal('@/asset/thering-couple.jpg')" class="thumbnail" alt="thumbnail from assets" /> 
       -->
       <img :src="theringCoupleImage" @click="openModal(theringCoupleImage)"
        class="thumbnail"
        alt="thumbnail" />

    </div>

    <!-- Modal for viewing full-size images -->
    <div v-if="selectedImage" class="modal" @click.self="closeModal">
      <span class="close" @click="closeModal">&times;</span>
      <img class="modal-content" :src="selectedImage" alt="full size" />
    </div>
  </div>
</template>

<script>
import theringCoupleImage from '~/asset/thering-couple.jpg';
export default {
  data() {
    return {
      theringCoupleImage,
      // selectedImage: null, // Stores the selected image URL
      // images: [
      //   'https://pagedone.io/asset/uploads/1712568734.png',
      //   'https://pagedone.io/asset/uploads/1712568734.png',
      //   'https://pagedone.io/asset/uploads/1712568734.png',
      //   'https://pagedone.io/asset/uploads/1712568734.png',
      //   'https://pagedone.io/asset/uploads/1712568734.png',
      //   'https://pagedone.io/asset/uploads/1712568734.png',
        
      // ] // Array of image URLs
    }
  },
  methods: {
    openModal(image) {
      this.selectedImage = image; // Set selected image for modal
    },
    closeModal() {
      this.selectedImage = null; // Close the modal by resetting the selected image
    }
  }
}
</script>