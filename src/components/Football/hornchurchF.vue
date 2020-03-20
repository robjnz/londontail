<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        Hornchurch
      </h2>
      <g-link href="http://bit.ly/2Tkk0z4" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/hornchurch.jpg"
          alt   = "Hornchurch"
      /></g-link>
      <p class="text-blue-200 text-center">
        The Stadium<br />
        Bridge Avenue<br />
        Upminster Essex

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/2Tj94li"
          target = "_blank"
        >
          RM14 2LX
        </g-link>
        <br /><br />
        <!-- HornchurchFC -->
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sat 4 April 3 pm <br /><span class="text-red-700">V</span>
        <br />Carshalton
      </p>

      <!--
Mon 13 April 2020 @ 3pm <br>V<br>East Thurrock<br>
Sat 18 April 2020 @ 3pm <br>V<br>Gray Wanderers<br>
-->
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2Tkk0z4"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
