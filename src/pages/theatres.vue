<template>
  <Layout>
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-16 text-4xl text-red-600">
          <span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span>
        Theatres
      </h1>
      <!--<date class="ml-8" />-->
      <br />

      <div class="grid sm:flex">
        <barking /><!--Broadway Theatre Barking-->
        <ilford /><!--ilford-->
        <barking /><!--Faces -->
      </div>
     
    </div>
    <br />
  </Layout>
</template>

<script>
import barking from "@/components/Theatres/barking";
import ilford from "@/components/Theatres/ilford";


import bar from "@/components/Nightclubs/bar";
import faces from "@/components/Nightclubs/faces";
import jhankaar from "@/components/Nightclubs/jhankaar";
import kings from "@/components/Nightclubs/kings";
import xoyo from "@/components/Nightclubs/xoyo";

import date from "@/components/Home/date";

export default {
  metaInfo: {
    title: "Theatres",
    meta : [
      {
        name   : "description",
        content: 
          "Whats on at Local Theatres In East London for Day Out."
      }
    ]
  },
  components: {
    barking,
    ilford,
    bar,
    faces,
    jhankaar,
    kings,
    xoyo,
    date
  }
};
</script>

<style>

</style>
