<template>
  <div>
    <img :src="theringCoupleImage" alt="The Ring Couple" />
  </div>
</template>

<script>
import theringCoupleImage from '~/assets/thering-couple.jpg';

export default {
  data() {
    return {
      theringCoupleImage,
    };
  },
};
</script>

<style>
/* Your styles here */
</style>
