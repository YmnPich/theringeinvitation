<template>
  <section class="py-24" style="width: 390px; margin: auto">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 overflow-hidden">
      <div class="mx-auto w-auto relative">
        <div class="swiper-container gallery-top w-full md:w-[1028px] mx-auto xl:overflow-hidden pt-6">
          <div class="swiper-wrapper w-max mx-auto mb-5 flex gap-3">
            <div class="swiper-slide fixed-size-image">
              <img class="rounded-xl object-cover" src="https://pagedone.io/asset/uploads/1712568734.png" alt="Watch image" />
            </div>
            <div class="swiper-slide fixed-size-image">
              <img class="rounded-xl object-cover" src="https://pagedone.io/asset/uploads/1712569721.png" alt="Watch image" />
            </div>
            <div class="swiper-slide fixed-size-image">
              <img class="rounded-xl object-cover" src="https://pagedone.io/asset/uploads/1712569721.png" alt="Watch image" />
            </div>
            <div class="swiper-slide fixed-size-image">
              <img class="rounded-xl object-cover" src="https://pagedone.io/asset/uploads/1712569721.png" alt="Watch image" />
            </div>
            </div>
        </div>
      </div>
    </div>
  </section>
</template>
    
    <script>
    import Swiper from 'swiper'; // Import Swiper.js
    
    export default {
      mounted() {
        // Initialize Swiper after the component mounts
        this.initSwiper();
      },
      methods: {
        initSwiper() {
          const swiper = new Swiper('.gallery-top', {
            spaceBetween: 20,
            slidesPerView: 3,
            parallax: true,
            centeredSlides: true,
            loop: true,
            autoplay: true,
            autoplaySpeed: 2000, // Adjust autoplay speed (milliseconds)
            slideToClickedSlide: true,
            paginationClickable: true,
            navigation: {
              nextEl: '.swiper-button-next',
              prevEl: '.swiper-button-prev'
            },
            breakpoints: {
              1920: {
                slidesPerView: 3,
                spaceBetween: 20,
              },
              1400: {
                slidesPerView: 3,
                spaceBetween: 20,
                centeredSlides: true
              },
              900: {
                slidesPerView: 3,
                spaceBetween: 15,
                centeredSlides: true
              },
              200: {
                slidesPerView: 2,
                spaceBetween: 15
              }
            },
          });
        }
      }
    };
    </script>