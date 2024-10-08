<template>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display+SC:ital,wght@0,400;0,700;0,900;1,400;1,700;1,900&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Alex+Brush&family=Playfair+Display+SC:ital,wght@0,400;0,700;0,900;1,400;1,700;1,900&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Alex+Brush&family=Playfair+Display+SC:ital,wght@0,400;0,700;0,900;1,400;1,700;1,900&family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
    <!-- <link href = "/asset/main1.scss"> -->
    <div class = "mainContainer">
      <!-- cover part -->
      <img src="/asset/cover.png" alt="Discover Nuxt 3" />
      <h1 class = "coupleName">SEBASTIAN & RACHELLE</h1>
      <div class = "name-bar"></div>
      <div class = "text-bar">invite you to join us</div>
      <!-- end of cover part -->

      <!-- thank part -->
      <div class = "text" style = "margin-top: 60px">IN THE CELEBRATION</div>
      <div class = "text">OF THEIR</div>
      <img style = "width: 305px; height: 103px; margin: auto; margin-top: 20px; margin-bottom: 40px;" src="/asset/wedding.png" alt="Discover Nuxt 3" />
      <table style = "margin: auto;">
        <tr>
        <td style="padding-right: 10px; font-weight: 700;">MR. CHAN SAVOEUN</td>
        <td style="padding-right: 10px;font-weight: 700;">MR. PHONG NARONG</td>
      </tr>
      <tr>
        <td style="padding-right: 10px;font-weight: 700;">MR. CHAN SAVOEUN</td>
        <td style="padding-right: 10px;font-weight: 700;">MR. PHONG NARONG</td>
      </tr>
      </table>
      <div class = "thankContent">
        Cordinally request the honor of your presence on the auspicious occasion of the wedding our children
      </div>
      <table>
        <tr>
          <td style="padding: 10px;">
            <div>GROOM</div>
            <div style = "font-weight: 700;">DEVIS DEVISTIAN</div>
          </td>
          <td><img style = "width: 140px; height: 133px;"src="/asset/coupleLogo.png" alt="Image"></td>
          <td style="padding: 10px;">
            <div>BRIDE</div>
            <div style = "font-weight: 700;">DANIEL RACHELLE</div>
          </td>
        </tr>
      </table>
      <div class = "month">
        february
      </div>
      <div class="date-container">
        <div>
            <table>
                <tr>
                    <td><div class = "date-line" style = "background-color: #9b6738;"></div></td>
                </tr>
                <tr>
                    <td><div class = "day"style = "font-family: roboto; font-size: 16px;">SATURDAY</div></td>
                </tr>
                <tr>
                    <td><div class = "dates-line" style = "background-color: #9b6738;"></div></td>
                </tr>
            </table>
        </div>
        <!-- <span class="day">SATURDAY</span> -->
        <!-- <span class="date">..</span> -->
        <span class="time">
            <table>
                <tr>
                    <td style = "font-family: roboto; font-size: 32px; font-weight: 600">28</td>
                </tr>
                <tr><td style = "font-family: roboto;font-size: 14px;">2024</td></tr>
            </table>
        </span>
        <span class="year">
            <table>
                <tr>
                    <td><div class = "date-line" style = "background-color: #9b6738;"></div></td>
                </tr>
                <tr>
                    <td><div class = "day" style = "font-family: roboto; font-size: 16px;">AT 2:30 PM</div></td>
                </tr>
                <tr>
                    <td><div class = "dates-line"style = "background-color: #9b6738;"></div></td>
                </tr>
            </table>
        </span>
        
    </div>
      <!-- end of thank part -->

      <!-- wedding program part -->
      <img class = "wedding-timelines"src = "/asset/wedding-timeline.png">
      <div class = "main-tab">
        <div class = "tab-box">
          <button class = "tab_btn active"> 27 FEB 2024</button>
          <button class = "tab_btn"> 28 FEB 2024</button>
          <div class = "line"></div>
        </div>
        <div class = "content-box">
          <div class="content active">
            <div class = "header">AFTERNOON CEREMONY</div>
            <div class = "vertical-line"></div>
            <div class = "event-text">3:00 PM</div>
            <div class = "event-text">Monk's Blessing</div>
  
            <div class = "vertical-line"></div>
            <div class = "event-text">5:00 PM</div>
            <div class = "event-text">
              Respectfully invite hornor guests at the bride's house
              Street 580, Sangkat Boeung Kak II, Khan Toul Kork
              Phnom Penh
            </div>
            <!-- <div class = "map-content">
              <table>
                <tr>
                  <td>
                    <img style="width: 45px; height: 43px;" src="/asset/googlemap-trans.png">
                  </td>
                  <td>
                    <div class = "event">Event location</div>
                  </td>
                </tr>
              </table>
            </div> -->
            <button class = "map-content">
              <a href="https://maps.app.goo.gl/UpFyxGX6A5TChtGZA">
                <table>
                <tr>
                  <td>
                    <img style="width: 45px; height: 43px;" src="/asset/googlemap-trans.png">
                  </td>
                  <td>
                    <div class = "event">Event location</div>
                  </td>
                </tr>
              </table>
              </a>
            </button>
          </div>
          <div class="content">
            <div class = "header">MORNING CEREMONY</div>
            <div class = "vertical-line"></div>
            <div class = "event-text">6:30 AM</div>
            <div class = "event-text">assemble hornor guest to be ready Offering made in the Toul Kork district (Bride's house) during the processional rite</div>
  
            <div class = "vertical-line"></div>
            <div class = "event-text">7:30 AM</div>
            <div class = "event-text">
                Offering during processtional rite
            </div>
  
            <div class = "vertical-line"></div>
            <div class = "event-text">8:00 AM</div>
            <div class = "event-text">
                Sla Sating Ceremony
            </div>
  
            <div class = "vertical-line"></div>
            <div class = "event-text">8:30 AM</div>
            <div class = "event-text">
                Ring Ceremony
            </div>
  
            <div class = "vertical-line"></div>
            <div class = "event-text">9:00 AM</div>
            <div class = "event-text">
                Hair Cutting Ceremony
            </div>
  
            <div class = "vertical-line"></div>
            <div class = "event-text">10:00 AM</div>
            <div class = "event-text">
                Sacrifice Ceremony , hand-typing Ceremony and sprikling of flowers
            </div>
  
            <div class = "vertical-line"></div>
            <div class = "event-text">12:00 AM</div>
            <div class = "event-text">
              Respectfully Invite hornor guests having lunch at Bride's house, Street 580, Sangkat Boeung Kak II, Khan Toul Kork
              Phnom Penh
            </div>
  
            <div class = "header" style = "margin-top: 40px">EVENING CEREMONY</div>
            <div class = "vertical-line"></div>
            <div class = "event-text">5:00 PM</div>
            <div class = "event-text">
              Respectfully Invite guests to have dinner at the center Chroy Changvar International Convention and Exhibition Center (OCIC) F&G Building
            </div>
            <button class = "map-content">
              <a href="https://maps.app.goo.gl/UpFyxGX6A5TChtGZA">
                <table>
                <tr>
                  <td>
                    <img style="width: 45px; height: 43px;" src="/asset/googlemap-trans.png">
                  </td>
                  <td>
                    <div class = "event">Event location</div>
                  </td>
                </tr>
              </table>
              </a>
            </button>
          </div>
          <!-- end of weddingprogram part -->

          <!-- photo gallery part -->
          <div class = "row-content">
            <table>
              <tr>
                <td>
                  <div class ="bar"></div>
                </td>
                <td>
                  <div class ="mid-text">PHOTO GALLERY</div>
                </td>
                <td>
                  <div class ="bar"></div>
                </td>
              </tr>
            </table>
          </div>
          <div>
            <table>
              <tr>
                <td>
                  <img style = "width: 144px;height: 216px;padding-right: 5px;" src="https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080" @click="openModal('https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080')"
                    class="thumbnail"
                    alt="thumbnail" />
                </td>
                <td>
                  <!-- <img style = "width: 201px; height: 108px ; object-fit:cover;"src = "https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080">
                  <img style = "width: 201px; height: 108px; object-fit:cover; padding-top: 5px"src = "https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080"> -->
                  <img style = "width: 201px; height: 108px ; object-fit:cover;" src="https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080" @click="openModal('https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080')"
                    class="thumbnail"
                    alt="thumbnail" />
                    <img style = "width: 201px; height: 108px; object-fit:cover; padding-top: 5px" src="https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080" @click="openModal('https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080')"
                    class="thumbnail"
                    alt="thumbnail" />
                </td>
                
              </tr>        
            </table>
            <!-- <img style = "width: 348px; height: 220px ; object-fit:cover; margin-top: 5px;"src = "https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080"> -->
            <img style = "width: 348px; height: 220px ; object-fit:cover; margin-top: 5px;" src="https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080" @click="openModal('https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080')"
                    class="thumbnail"
                    alt="thumbnail" />
            <table style = "margin-top: 5px;">
              <tr>
                <td>
                  <!-- <img style = "width: 172.5px; height: 243px ; object-fit:cover;padding-right: 5px;"src = "https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080"> -->
                  <img style = "width: 172.5px; height: 243px ; object-fit:cover;padding-right: 5px;" src="https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080" @click="openModal('https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080')"
                    class="thumbnail"
                    alt="thumbnail" />
                </td>
                <td>
                  <!-- <img style = "width: 172.5px; height: 243px ; object-fit:cover;"src = "https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080"> -->
                  <img style = "width: 172.5px; height: 243px ; object-fit:cover;padding-right: 5px;" src="https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080" @click="openModal('https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080')"
                    class="thumbnail"
                    alt="thumbnail" />
                </td>
              </tr>
            </table>
            <!-- <img onclick = "FullView(this.src)"style = "width: 348px; height: 220px ; object-fit:cover; margin-top: 5px;"src = "https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080"> -->
            <img style = "width: 348px; height: 220px ; object-fit:cover; margin-top: 5px;" src="https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080" @click="openModal('https://images.unsplash.com/photo-1640654438886-2839af1c6287?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NTYyMDF8MHwxfHNlYXJjaHw2fHxjb3VwbGUlMjB3ZWRkaW5nJTIwcGhvdG98ZW58MHx8fHwxNzIyMzUzNzg0fDA&ixlib=rb-4.0.3&q=80&w=1080')"
                    class="thumbnail"
                    alt="thumbnail" />

            <!-- end of photo gallery part -->

            <!-- QR Code part -->
            <div class = "main-qr" style = "padding-bottom : 20px;">
              <div style = "text-align: center;padding-top: 30px;margin-bottom: 30px; font-size: 20px; font-weight: 600;font-family: Playfair Display SC, serif;">SCAN OR CLICK ON QR CODE</div>
              <img class = "qr-code" style = "margin-bottom: 20px;"src = "/asset/QR-DOLLAR.png">
              <img class = "qr-code" src = "/asset/QR-RIEL.png">
            </div>
          </div>
          <div v-if="selectedImage" class="modal" @click.self="closeModal">
      <span class="close" @click="closeModal">&times;</span>
      <img class="modal-content" :src="selectedImage" alt="full size" />
    </div>
          <!-- <div id = "FullImageView">
            <img id = "FullImage">
          </div> -->
          <!-- end of QR Code part -->

          <!-- powered part -->
          <div class = "app-power"> Powered By : The Wedding App</div>
          <div class = "icon">
            <table>
              <tr>
                <td>
                  <img class = "logo-size" src = "/asset/facebook-icon.png">
                </td>
                <td>
                  <img class = "logo-size" src = "/asset/weddingapp-logo.jpg">
                </td>
                <td>
                  <img src="/asset/instagram-icon.png" alt="" class="logo-size">
                </td>
              </tr>
            </table>
          </div>
        </div>
        <!-- end of powered part -->

        
      </div>
    </div>
  </template>
  <script>
  import theringCoupleImage from '~/asset/thering-couple.jpg';
  
  export default {
    data() {
      return {
        theringCoupleImage,
        selectedImage: null, // Stores the selected image URL
        // images: [
        //   'https://pagedone.io/asset/uploads/1712568734.png',
        //   'https://pagedone.io/asset/uploads/1712568734.png',
        //   'https://pagedone.io/asset/uploads/1712568734.png',
        //   'https://pagedone.io/asset/uploads/1712568734.png',
        //   'https://pagedone.io/asset/uploads/1712568734.png',
        //   'https://pagedone.io/asset/uploads/1712568734.png',
        // ] // Array of image URLs
      };
    },
    mounted() {
      const tabs = document.querySelectorAll('.tab_btn');
      const contentDisplays = document.querySelectorAll('.content'); // Use plural form for clarity
  
      function handleTabClick(event) {
        // Remove active class from all tabs
        tabs.forEach(tab => tab.classList.remove('active'));
  
        // Add active class to the clicked tab
        event.target.classList.add('active');
  
        // Animate line under active tab (assuming line element exists)
        const line = document.querySelector('.line');
        if (line) {
          line.style.width = event.target.offsetWidth + "px";
          line.style.left = event.target.offsetLeft + "px";
        }
  
        // Hide all content displays
        contentDisplays.forEach(content => content.classList.remove('active'));
  
        // Show the content display corresponding to the clicked tab
        const clickedTabIndex = Array.from(tabs).indexOf(event.target);
        if (clickedTabIndex !== -1) {
          contentDisplays[clickedTabIndex].classList.add('active');
        } else {
          console.error('Clicked tab not found in content displays. Check for consistency.');
        }
      }
  
      // Attach click event listener to all tabs
      tabs.forEach(tab => tab.addEventListener('click', handleTabClick));
    },
    methods: {
      openModal(image) {
        this.selectedImage = image; // Set selected image for modal
      },
      closeModal() {
        this.selectedImage = null; // Close the modal by resetting the selected image
      },
      FullView(ImgLink) {
        document.getElementById("FullImage").src = ImgLink;
        document.getElementById("FullImageView").style.display = "block"; 
      }
    }
  }
  </script>
  