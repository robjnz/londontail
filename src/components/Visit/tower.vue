<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"> Tower Of London</H2>
      <g-link href="http://bit.ly/2OKnQ4U" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/visit/tower.jpg"
          fluid-grow
          alt = "Tower Of London"
      /></g-link>
      <p class="text-blue-200">
        Tower of London<br />Wapping London 

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/38OAXr8"
          target = "_blank"
        >
         EC3N 4AB
        </g-link>
      </p>
      <br /><br /><br />
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2OKnQ4U"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>

