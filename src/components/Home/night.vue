<template>
  <div class="m-4 p-4 w-auto rounded-lg">
    <div class="p-6">
      <h2 class="text-3xl text-blue-500">
        <span>
          <i class="fas fa-glass-cheers"></i>
        </span>
        Nightclubs
      </h2>
      
     <!--march-->
        <h3 class="text-xl text-pink-300">
      <span style="font-size: 1em;">
        <i class="far fa-calendar-alt"></i>
      </span>
      Fri 20 March
    </h3>
    <div class="grid sm:flex">
        <atik /><!--atik-->
      </div>
      <br />
<!--27 march-->
       <h3 class="text-xl text-pink-300">
      <span style="font-size: 1em;">
        <i class="far fa-calendar-alt"></i>
      </span>
      Fri 27 March
    </h3>
    <div class="grid sm:flex">
        <xoyo /><!--xoyo-->
      </div>
      <!--27 march -->
      <br />
      <!--april-->
       <h3 class="text-xl text-pink-300">
      <span style="font-size: 1em;">
        <i class="far fa-calendar-alt"></i>
      </span>
      Fri 3 April
    </h3>
    <div class="grid sm:flex">
        <faces /><!--faces-->
      </div>
      

      <g-link class="text-blue-500 text-2xl hover:text-white" to="/nightclubs"
        >More Nightclubs</g-link
      >
    </div>
  </div>
</template>

<script>
import atik from "@/components/Nightclubs/atik";
import faces from "@/components/Nightclubs/faces";
import xoyo from "@/components/Nightclubs/xoyo";




export default {
  components: {
    atik,
    faces,
    xoyo,
   
    
  }
};
</script>
