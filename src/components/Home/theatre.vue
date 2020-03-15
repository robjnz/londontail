<template>
  <div class="m-4 p-4 w-auto rounded-lg">
    <div class="p-6">
      <h2 class="text-3xl text-blue-500">
        <span>
          <i class="fas fa-theater-masks"></i>
        </span>
        Theatres
      </h2>

      <!--march-->
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sun 15 March
      </h3>
      <div class="grid sm:flex"><barking /><!--barking--></div>
      <br />
      <!--27 march-->
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sun 22 March
      </h3>
      <div class="grid sm:flex">
        <greenwich/><!--Greenwich Theatre-->
        <hackney /><!--Hackney Empire-->
      </div>
      <!--27 march -->
      <br />
      <!--april-->
     

      <g-link class="text-blue-500 text-2xl hover:text-white" to="/theatres"
        >More Theatres</g-link
      >
    </div>
  </div>
</template>

<script>
import barking from "@/components/Theatres/barking";
import greenwich from "@/components/Theatres/greenwich";
import hackney from "@/components/Theatres/hackney";

import Blank from "@/components/Home/Blank";
import atik from "@/components/Nightclubs/atik";


export default {
  components: {
    Blank,
    barking,
    greenwich,
    hackney,
    atik,
    
    
  }
};
</script>
