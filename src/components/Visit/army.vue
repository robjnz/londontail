<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  National Army Museum</H2>
      <g-link href="https://bit.ly/2SrND1S" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1588416158/army_mzyxxl.jpg"
          alt   = " National Army Museum"
      /></g-link>
      <p class="text-blue-200">
       Royal Hospital Road<br />Chelsea London 



        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/3b2VxFv"
          target = "_blank"
        >
          SW3 4HT
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
 The National Army Museum is a<br /> leading authority on the British Army...... 
<input id="read-more-army-1" class="read-more-army" type="checkbox">

  <div class="read-more-content">
<br />
 and its impact on society past <br />and present.revealing true stories <br />of ordinary people with <br />extraordinary responsibilities.
</div>
<label class="read-more-army-label text-red-700 hover:text-white" for="read-more-army-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/2SrND1S"
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
.read-more-army {
  display: none;
}
.read-more-army-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-army-label:after {
  content: "More";
  display: inline-block;
}
.read-more-army:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-army:checked + .read-more-content + .read-more-army-label:after {
  content: "Less";
}
</style>
