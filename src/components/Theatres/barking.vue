<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"> Broadway Theatre Barking</H2>
      <g-link href="http://bit.ly/2WkdIT0" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1582957572/poppins_spyysw.jpg"
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
    
 <div class="comment more text-blue-200">
	Mary Poppins, a mystical nanny returns to London to save the day in this musical dance show suitable for all.

</div>


     
<script>
$(document).ready(function() {
	var showChar     = 100;
	var ellipsestext = "...";
	var moretext     = "read more";
	var lesstext     = "read less";
	$('.more').each(function() {
		var content = $(this).html();

		if(content.length > showChar) {

			var c = content.substr(0, showChar);
			var h = content.substr(showChar-1, content.length - showChar);

			var html = c + '<span class="moreellipses">' + ellipsestext+ '&nbsp;</span><span class="morecontent"><span>' + h + '</span>&nbsp;&nbsp;<a href="" class="morelink">' + moretext + '</a></span>';

			$(this).html(html);
		}

	});

	$(".morelink").click(function(){
		if($(this).hasClass("less")) {
			$(this).removeClass("less");
			$(this).html(moretext);
		} else {
			$(this).addClass("less");
			$(this).html(lesstext);
		}
		$(this).parent().prev().toggle();
		$(this).prev().toggle();
		return false;
	});
});

</script>
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


</style>



