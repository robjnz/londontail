<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Epping Forest</H2>
      <g-link href="http://bit.ly/2ywqe5a" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/visit/epping.jpg"
          fluid-grow
          alt = "Epping Forest"
      /></g-link>
      <p class="text-blue-200">
        Paul's Nursery Road<br />
        High Beach Essex

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/3cxGdTf"
          target = "_blank"
        >
          IG10 4AF
        </g-link>
     <p>
       <br /><br /><br />
     </p>
    
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2ywqe5a"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
