<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Valentines Mansion</H2>
      <g-link href="http://bit.ly/38ReARM" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/visit/valentines.jpg"
          fluid-grow
          alt = "Valentines Mansion"
      /></g-link>
      <p class="text-blue-200">
        Emerson Road<br />
        Ilford Essex

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/32JR9IP"
          target = "_blank"
        >
          IG1 4XA
        </g-link>
      </p>
      <h5 class="text-2xl text-pink-300">Closed</h5>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        <!--Fri 13 March to Fri 3 April-->
      </p>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/2xZFMRL"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
