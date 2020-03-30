<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Eltham Palace</H2>
      <g-link href="http://bit.ly/3aI2oUI" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/visit/eltham.jpg"
          fluid-grow
          alt = "Eltham Palace"
      /></g-link>
      <p class="text-blue-200">
        Court Yard Eltham <br /> Greenwich London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/3cRYYR9"
          target = "_blank"
        >
          SE9 5QE
        </g-link>
      </p>

      <h5 class="text-2xl text-pink-300">Closed</h5>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        <!--Sat 4 - Sun 19 April-->
      </p>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/3aI2oUI"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>

