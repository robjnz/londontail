<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Bexley Park Wood</H2>
      <g-link href="http://bit.ly/2E7182l" target="_blank"
        ><g-image class="w-auto h-auto"
          src = "@/images/visit/bexleywoods.jpg"
          fluid-grow
          alt = "Bexley Park Wood"
      /></g-link>
      <p class="text-blue-200">
        Brigden Road <br />Bexley London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/39yBiiQ"
          target = "_blank"
        >
          DA5 3PT
        </g-link>
        <br /><br /><br />
      </p>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2E7182l"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
