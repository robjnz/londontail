<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Docklands Museum</H2>
      <g-link href="http://bit.ly/2EyBcwJ" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/visit/docklands.jpg"
          fluid-grow
          alt = "Docklands Museum"
      /></g-link>
      <p class="text-blue-200">
        No1 Warehouse<br />
        West India Quay London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/2vX30Y2"
          target = "_blank"
        >
          E14 4AL
        </g-link>
      </p>
      
      <h5 class=" mb-4 text-2xl text-pink-300">Closed</h5>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2EyBcwJ"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
