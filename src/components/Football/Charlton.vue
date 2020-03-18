<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        Charlton
      </h2>
      <g-link href="http://bit.ly/2G0A3Pe" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/charlton.png"
          alt   = "Charlton"
      /></g-link>
      <p class="text-blue-200 text-center">
        The Valley<br />Floyd Road Charlton <br />London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/2wLc5Dc"
          target = "_blank"
        >
          SE7 8BL
        </g-link>
        
      </p>
<br />
       <!-- #CAFC -->
       <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sat 4 April 3 pm  <br /><span class="text-red-700">V</span> <br />Millwall
        
        

     <!--
Mon 13 April 2020 @ 3pm <br>V<br>Reading<br>
Sat 25 April 2020 @ 3pm <br>V<br>Wigan Athletic<br>
-->
    </p>

      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2G0A3Pe"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
