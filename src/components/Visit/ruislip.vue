<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Ruislip Woods</H2>
      <g-link href="https://bit.ly/2xgbAlu" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1586770692/ruislip_nbpi8d.jpg"
          alt   = "ruislip woods"
      /></g-link>
      <p class="text-blue-200">
        Ducks Hill Road <br /> Ruislip London


        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2VnbQad"
          target = "_blank"
        >
          HA4 7TS
        </g-link>
      </p>
      
      <h5 class=" mb-4 text-2xl text-pink-300">Open</h5>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
          These Woods were first recorded in <br />the Doomsday Book in 1068......

<input id="read-more-ruislip-1" class="read-more-ruislip" type="checkbox">

  <div class="read-more-content">
<br />
 They comprise of mainly Oaks,<br /> Silver Birches, Hornbeam,<br /> Beech and Hazel trees. 
 </div>
<label class="read-more-ruislip-label text-red-700 hover:text-white" for="read-more-ruislip-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/2xgbAlu"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>

<style>


.read-more-content {
  max-height: 0;
  overflow  : hidden;
  transition: max-height .5s ease;
}
.read-more-ruislip {
  display: none;
}
.read-more-ruislip-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-ruislip-label:after {
  content: "More";
  display: inline-block;
}
.read-more-ruislip:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-ruislip:checked + .read-more-content + .read-more-ruislip-label:after {
  content: "Less";
}
</style>
