<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span>  Arts Depot</H2>
      <g-link href="https://bit.ly/33VAjag" target="_blank"
        ><g-image
       class = "w-auto h-auto"
       src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1585492952/artsdepot_yl9b6s.jpg"
       alt   = " Arts Depot poster"
      /></g-link>
       
      <p class="text-blue-200"> 
         5 Nether Street Tally Ho Corner<br /> North Finchley London 
        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2QQ9xeg"
          target = "_blank"
        >
          N12 0GA
        </g-link>
      </p>
      <h5 class="text-2xl text-pink-300">Closed</h5>
      <p class="text-pink-300">
          <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       <!-- Sun 15 - Sat 28 March-->
      </p>
    
<!--
<article class="text-blue-200">
   Mary Poppins, a mystical nanny returns <br />to London....
  <input id="read-more-arts-1" class="read-more-arts" type="checkbox">
  <div class="read-more-content">
         To save the day in this musical dance <br />show suitable for all.

  </div>
  <label class="read-more-arts-label text-red-700 hover:text-white" for="read-more-arts-1">Read </label>
</article>
    --> 

<br />
<g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/33VAjag"
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
.read-more-arts {
  display: none;
}
.read-more-arts-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-arts-label:after {
  content: "More";
  display: inline-block;
}
.read-more-arts:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-arts:checked + .read-more-content + .read-more-arts-label:after {
  content: "Less";
}
</style>