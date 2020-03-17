<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Havering Country Park</H2>
      <g-link href="http://bit.ly/2vYTVxT" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/visit/haveringpark.jpg"
          fluid-grow
          alt = "Havering Country Park"
      /></g-link>
      <p class="text-blue-200">
       Pinewood Road<br /> Havering-Atte-Bower Essex 

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/2Q6imjC"
          target = "_blank"
        >
          RM4 1PB
        </g-link>
      </p>

     
      <br /><br /><br />
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2vYTVxT"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
