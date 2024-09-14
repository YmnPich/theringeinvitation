<template>
  <div class="flex items-start justify-center w-full gap-4 count-down-main" style = "margin-top : 10px">
      <div class="timer w-16">
      <div
      class=" bg-indigo-600 py-4 px-2 rounded-lg overflow-hidden">
      <h3
        class="countdown-element days font-Cormorant font-semibold text-2xl text-white text-center">
      </h3>
      </div>
      <p class="text-lg font-Cormorant font-medium text-gray-900 mt-1 text-center w-full">days</p>
      </div>
      <h3 class="font-manrope font-semibold text-2xl text-gray-900">:</h3>
      <div class="timer w-16">
      <div
      class=" bg-indigo-600 py-4 px-2 rounded-lg overflow-hidden">
      <h3
        class="countdown-element hours font-Cormorant font-semibold text-2xl text-white text-center">
      </h3>
      </div>
      <p class="text-lg font-Cormorant font-normal text-gray-900 mt-1 text-center w-full">hours</p>
      </div>
      <h3 class="font-manrope font-semibold text-2xl text-gray-900">:</h3>
      <div class="timer w-16">
      <div
      class=" bg-indigo-600 py-4 px-2 rounded-lg overflow-hidden">
      <h3
        class="countdown-element minutes font-Cormorant font-semibold text-2xl text-white text-center">
      </h3>
      </div>
      <p class="text-lg font-Cormorant font-normal text-gray-900 mt-1 text-center w-full">minutes</p>
      </div>
      <h3 class="font-manrope font-semibold text-2xl text-gray-900">:</h3>
      <div class="timer w-16">
      <div
      class=" bg-indigo-600 py-4 px-2 rounded-lg overflow-hidden ">
      <h3
        class="countdown-element seconds font-Cormorant font-semibold text-2xl text-white text-center animate-countinsecond">
      </h3>
      </div>
      <p class="text-lg font-Cormorant font-normal text-gray-900 mt-1 text-center w-full">seconds</p>
      </div>
      </div>
                          
</template>
<script>

export default {
  mounted() {
    let dest = new Date("2024-09-15 00:00:00").getTime();
      let x = setInterval(function () {
      let now = new Date().getTime();
      let diff = dest - now;
      
        // Check if the countdown has reached zero or negative
  if (diff <= 0) {
    clearInterval(x); // Stop the countdown
    return; // Exit the function
  }

  let days = Math.floor(diff / (1000 * 60 * 60 * 24));
  let hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  let minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
  let seconds = Math.floor((diff % (1000 * 60)) / 1000);


  days = String(days).padStart(2, '0');
  hours = String(hours).padStart(2, '0');
  minutes = String(minutes).padStart(2, '0');
  seconds = String(seconds).padStart(2, 
 '0');

  // Get elements by class name
  let countdownElements = document.getElementsByClassName("countdown-element");

  // Loop through the elements and update their content
  for (let i = 0; i < countdownElements.length; i++) {
    let className = countdownElements[i].classList[1]; // Get the second class name
    switch (className) {
      case "days":
        countdownElements[i].innerHTML = days;
        break;
      case "hours":
        countdownElements[i].innerHTML = hours;
        break;
      case "minutes":
        countdownElements[i].innerHTML = minutes;
        break;
      case "seconds":
        countdownElements[i].innerHTML = seconds;
        break;
      default:
        break;
    }
  }
}, 1000);
  }
};
</script>