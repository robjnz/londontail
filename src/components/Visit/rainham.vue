<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Rainham Hall</H2>
      <g-link href="http://bit.ly/2pV7NSZ" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/visit/rainham.jpg"
          fluid-grow
          alt = "Rainham Hall"
      /></g-link>
      <p class="text-blue-200">
        The Broadway <br />Rainham Essex 

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/39NSUaq"
          target = "_blank"
        >
         RM13 9YN
        </g-link>
         <h5 class="text-2xl text-pink-300">Closed</h5>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        <!--Sun 22 March-->
      </p>
        
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2pV7NSZ"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>



