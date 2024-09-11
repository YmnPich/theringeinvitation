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
      <table>
        <img
          src="https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080"
          alt="Photo from Wedding Gallery"
          style="width: 348px; height: 220px ; object-fit:cover; margin-top: 5px;"
          @click="openFullImage('https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080')"
        />
        <img
          style="width: 348px; height: 220px ; object-fit:cover; margin-top: 5px;"
          src="https://images.unsplash.com/photo-1640654454393-d0a6efcef79f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHwyMnx8Y291cGxlJTIwd2VkZGluZyUyMHBob3RvfGVufDB8fHx8MTcyMjM1Mzc4NHww&ixlib=rb-4.0.3&q=80&w=1080"
          alt="Photo from Wedding Gallery"
          @click="openFullImage('https://images.unsplash.com/photo-1640654454393-d0a6efcef79f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHwyMnx8Y291cGxlJTIwd2VkZGluZyUyMHBob3RvfGVufDB8fHx8MTcyMjM1Mzc4NHww&ixlib=rb-4.0.3&q=80&w=1080')"
        />
      </table>
      <div id="FullImageView" style="display: none;">
        <img id="FullImage" />
        <button
          @click="closeFullImage"
          style="position: absolute; top: 10px; right: 10px; background-color: #fff; color: #000; border: none; padding: 10px; cursor: pointer;"
        >
          X
        </button>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
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
  };
  </script>