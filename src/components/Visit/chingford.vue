<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Chingford Sky Trail</H2>
      <g-link href="http://bit.ly/2THvCgW" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/visit/chingford.jpg"
          fluid-grow
          alt = "Chingford Sky Trail"
      /></g-link>
      <p class="text-blue-200">
        A406 Southend Road<br />
        Chingford London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/3aJKYXP"
          target = "_blank"
        >
          E4 8TA
        </g-link>

      </p>
              <h5 class=" mb-4 text-2xl text-pink-300">Closed</h5>

      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2THvCgW"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
