<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Hall Place & Gardens</H2>
      <g-link href="http://bit.ly/2QyDQ6A" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/visit/hallplace.jpg"
          fluid-grow
          alt = "Hall Place & Gardens"
      /></g-link>
      <p class="text-blue-200">
        Bourne Road<br />
        Bexley Kent

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/2ve9T6S"
          target = "_blank"
        >
          DA5 1PQ
        </g-link>
      </p>

     <h5 class="text-2xl text-pink-300">Mother's Day Afternoon Tea</h5>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        Sun 22 March
      </p>

      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2QyDQ6A"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
