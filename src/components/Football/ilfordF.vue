<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        Ilford
      </h2>
      <g-link href="http://bit.ly/399ayVZ" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/ilford.jpg"
          alt   = "Ilford"
      /></g-link>
      <p class="text-blue-200 text-center">
        Cricklefield Stadium<br />
      3 Cricklefield Place<br />
      Ilford Essex 

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/394xvtp"
          target = "_blank"
        >
          IG1 1FY
        </g-link>
        <br /><br />
        <!-- HornchurchFC -->
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sat 18 April 3 pm <br /><span class="text-red-700">V</span>
        <br />Saffron Walden
      </p>

       
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/399ayVZ"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
