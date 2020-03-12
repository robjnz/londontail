<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"> Horniman Museam & Park</H2>
      <g-link href="http://bit.ly/2ykLEm0" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/visit/horniman.jpg"
          fluid-grow
          alt = "Horniman Museam & Park"
      /></g-link>
      <p class="text-blue-200">
        100 London Road<br />Forest Hill London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/2TJinfz"
          target = "_blank"
        >
          SE23 3PQ
        </g-link>
      </p>

      <br /><br /><br />

      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2ykLEm0"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
