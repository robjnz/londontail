<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        West Ham
      </h2>
      <g-link href="http://bit.ly/2QrI8B7" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/west_ham.png"
          alt   = "west ham"
      /></g-link>
      <p class="text-blue-200 text-center">
        London stadium<br />Queen Elizabeth Olympic Park <br /> Stratford London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/3aiGMOK"
          target = "_blank"
        >
          E20 2ST
        </g-link>
        <br /><br />
        <!-- #WHUFC -->
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sat 18 April - 3 pm <br /><span class="text-red-700">V</span>
        <br />Burnley
      </p>

            <!--

Sat 18 April 2020 @ 3pm <br>V<br>Burnley<br>
Sat 2 May 2020 @ 3pm <br>V<br>Watford<br>
Sun 17 May 2020 @ 3pm <br>V<br>Aston Villa<br>
-->
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2QrI8B7"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
