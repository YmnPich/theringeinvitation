<template>
    <div class="row-content">
      <table>
        <tr>
          <td>
            <div class="bar"></div>
          </td>
          <td>
            <div class="mid-text">PHOTO GALLERY</div>
          </td>
          <td>
            <div class="bar"></div>
          </td>
        </tr>
      </table>
    </div>
    <div>
      <!-- <table>
        <template v-for="(imageUrl, index) in imageUrls" :key="index">
          <tr>
            <td>
              <img
                :src="imageUrl"
                alt="Photo from Wedding Gallery"
                style="width: 144px; height: 216px; padding-right: 5px;"
                @click="openFullImage(imageUrl)"
              />
            </td>
          </tr>
        </template>
      </table> -->
      <table>
        <template v-for="(imageUrl, index) in imageUrls" :key="index">
            <tr>
                <td>
                    <img
                        src="https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080"
                        alt="Photo from Wedding Gallery"
                        style="width: 144px; height: 216px; padding-right: 5px;"
                        @click="openFullImage(imageUrl)"
                    />
                </td>
                <td>
                    <img
                        src="https://images.unsplash.com/photo-1640654454393-d0a6efcef79f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHwyMnx8Y291cGxlJTIwd2VkZGluZyUyMHBob3RvfGVufDB8fHx8MTcyMjM1Mzc4NHww&ixlib=rb-4.0.3&q=80&w=1080"
                        alt="Photo from Wedding Gallery"
                        style="width: 201px; height: 108px ; object-fit:cover;"
                        @click="openFullImage(imageUrl)"
                    />
                    <img
                        src="https://images.unsplash.com/photo-1640654454393-d0a6efcef79f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHwyMnx8Y291cGxlJTIwd2VkZGluZyUyMHBob3RvfGVufDB8fHx8MTcyMjM1Mzc4NHww&ixlib=rb-4.0.3&q=80&w=1080"
                        alt="Photo from Wedding Gallery"
                        style="width: 201px; height: 108px; object-fit:cover; padding-top: 5px"
                        @click="openFullImage(imageUrl)"
                    />
                </td>
                
              </tr>   
        </template>     
        </table>
        <img
            src="https://images.unsplash.com/photo-1640654454393-d0a6efcef79f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHwyMnx8Y291cGxlJTIwd2VkZGluZyUyMHBob3RvfGVufDB8fHx8MTcyMjM1Mzc4NHww&ixlib=rb-4.0.3&q=80&w=1080"
            alt="Photo from Wedding Gallery"
            style="width: 348px; height: 220px ; object-fit:cover; margin-top: 5px;"
            @click="openFullImage(imageUrl)"
        />
        <img style = "width: 348px; height: 220px ; object-fit:cover; margin-top: 5px;"src = "https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080">
    </div>
    <div id="FullImageView" style="display: none;">
      <img id="FullImage" />
      <button @click="closeFullImage" style="position: absolute; top: 10px; right: 10px; background-color: #fff; color: #000; border: none; padding: 10px; cursor: pointer;">X</button>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        imageUrls: [
          // List of image URLs for the gallery
          "https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080",

          // ... other image URLs
        ],
        fullImageUrl: "", // Stores the URL of the currently opened full image
      };
    },
    methods: {
      openFullImage(imageUrl) {
        this.fullImageUrl = imageUrl;
        document.getElementById("FullImage").src = imageUrl;
        document.getElementById("FullImageView").style.display = "block";
      },
      closeFullImage() {
        this.fullImageUrl = "";
        document.getElementById("FullImageView").style.display = "none";
      },
    },
    // ... other code ...
  };
  </script>