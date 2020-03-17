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
<!--mon 16 march-->
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Tues 17 March
      </h3>
      <div class="grid sm:flex"><hornchurch /><!--romford--></div>
      <br />
      <!--end fri 13 march-->
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sun 15 March
      </h3>
      <div class="grid sm:flex"><barking /><!--barking--></div>
      <br />
<!-- end sun 15 March-->
<!--sat 21 march -->
       <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sat 21 March
      </h3>
      <div class="grid sm:flex"><hoxton /><!--hoxton--></div>
      <br />
      <!--end sat 21 march -->
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
     <!--24 march-->
 <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Tues 24 March
      </h3>
      <div class="grid sm:flex"><stratford /><!--stratford--></div>
      <br />
     <!--end 24 march-->
       
      <!--wed 25 march -->
      
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Wed 25 March
      </h3>
      <div class="grid sm:flex"><wilton /><!--wilton--></div>
      <br />
      <!--end wed 25 march-->
      
      <!--fri 27 march -->
      
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
       Fri 27 March
      </h3>
      <div class="grid sm:flex"><two/><!--02--></div>
      <br />
      <!--end fri 27 march-->
      <!--1 april-->
     <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Wed 1 April
      </h3>
      <div class="grid sm:flex"><ilford /><!--ilford--></div>
      <br />
<!--en 1 april -->

<!--2 april-->
     <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Thurs 2 April
      </h3>
      <div class="grid sm:flex"><yard /><!--yard--></div>
      <br />
<!--end 2 april -->
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
import hoxton from "@/components/Theatres/hoxton";
import ilford from "@/components/Theatres/ilford";
import hornchurch from "@/components/Theatres/hornchurch";
import stratford from "@/components/Theatres/stratford";
import two from "@/components/Theatres/two";
import wilton from "@/components/Theatres/wilton";
import yard from "@/components/Theatres/yard";

import Blank from "@/components/Home/Blank";



export default {
  components: {
    Blank,
    barking,
    greenwich,
    hackney,
    hornchurch,
    hoxton,
    ilford,
    stratford,
    two,
    wilton,
    yard,
  }
};
</script>
