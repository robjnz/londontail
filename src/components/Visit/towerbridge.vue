<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Tower Bridge</H2>
      <g-link href="https://bit.ly/2RFKCdU" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1515831480/tower_vow6im.jpg"
          alt   = "tower bridge"
      /></g-link>
      <p class="text-blue-200">
      Tower Bridge Road<br />London 


        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/34BkyWF"
          target = "_blank"
        >
          SE1 2UP
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
      <article class="text-blue-200">
Tower Bridge will transport<br /> you back to Victorian London......
<input id="read-more-towerbridge-1" class="read-more-towerbridge" type="checkbox">

  <div class="read-more-content">
<br />
telling the story of the city’s <br />defining landmark from <br />the very beginning.
<br /><br />visit its high-level <br />Walkways and Glass Floors.
 </div>
<label class="read-more-towerbridge-label text-red-700 hover:text-white" for="read-more-towerbridge-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/2RFKCdU"
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
.read-more-towerbridge {
  display: none;
}
.read-more-towerbridge-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-towerbridge-label:after {
  content: "More";
  display: inline-block;
}
.read-more-towerbridge:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-towerbridge:checked + .read-more-content + .read-more-towerbridge-label:after {
  content: "Less";
}
</style>
