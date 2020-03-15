<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"> Ilford</H2>
      <g-link href="http://bit.ly/2WkdIT0" target="_blank"
        ><g-image
          
          src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1582957572/poppins_spyysw.jpg"
          fluid-grow
          alt = "Docklands Museum"
      /></g-link>
       
      <p class="text-blue-200"> 
         Broadway<br /> Barking Essex
        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/3cXDRwZ"
          target = "_blank"
        >
          IG11 7LS
        </g-link>
      </p>
      <h5 class="text-2xl text-pink-300">Mary Poppins Reappears</h5>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        Sun 15 - 28 March
      </p>
    

<article class="text-blue-200">
   Mary Poppins, a mystical nanny returns to London....
  <input id="read-more-ilford-1" class="read-more-ilford" type="checkbox">
  <div class="read-more-content">
         To save the day in this musical dance show suitable for all.

  </div>
  <label class="read-more-ilford-label text-red-700 hover:text-white" for="read-more-ilford-1">Read </label>
</article>
     

<br />
<g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2WkdIT0"
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
.read-more-ilford {
  display: none;
}
.read-more-ilford-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-ilford-label:after {
  content: "More";
  display: inline-block;
}
.read-more-ilford:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-ilford:checked + .read-more-content + .read-more-ilford-label:after {
  content: "Less";
}
</style>