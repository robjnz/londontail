<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"
        ><span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        Royal Air Force Museum
</H2
      >
      <g-link href="https://bit.ly/3broAmB" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1585156962/airforce_ft0caa.jpg"
          fluid-grow
          alt = "Royal Air Force Museum"
      /></g-link>
      <p class="text-blue-200">
        Grahame Park Way<br /> Hendon London 
        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2WKtOpo"
          target = "_blank"
        >
           NW9 5LL
        </g-link>
      </p>
      
       <h5 class=" mb-4 text-2xl text-pink-300">Closed</h5>
      <article class="text-blue-200">
  Celebrates and commemorates<br /> the Royal Air Force 
....... 
  <input id="read-more-airforce-1" class="read-more-airforce" type="checkbox">
  <div class="read-more-content">
      <br />
The new innovative galleries<br /> explore the first 100 years<br /> of the RAF & its role today.

  </div>
  <label class="read-more-airforce-label text-red-700 hover:text-white" for="read-more-airforce-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/3broAmB"
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
.read-more-airforce {
  display: none;
}
.read-more-airforce-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-airforce-label:after {
  content: "More";
  display: inline-block;
}
.read-more-airforce:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-airforce:checked + .read-more-content + .read-more-airforce-label:after {
  content: "Less";
}
</style>
