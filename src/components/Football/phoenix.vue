<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        Phoenix Sports
      </h2>
      <g-link href="http://bit.ly/32GCH4e" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/phoenix.jpg"
          alt   = "Phoenix Sports"
      /></g-link>
      <p class="text-blue-200 text-center">
        The Mayplace Ground<br />
        Maylace Road East<br />
        Bexleyheath Kent

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/3cqBrqw"
          target = "_blank"
        >
          DA7 6JT
        </g-link>
        <br /><br />
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sat 25 April 3 pm <br /><span class="text-red-700">V</span>
        <br />Ramsgate
      </p>

      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/32GCH4e"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
