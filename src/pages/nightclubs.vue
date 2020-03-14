<template>
  <Layout>
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-16 text-4xl text-red-600">
        <span class="text-pink-300">
          <i class="fas fa-glass-cheers"></i>
        </span>
        Nightclubs
      </h1>
      <!--<date class="ml-8" />-->
      <br />

      <div class="grid sm:flex">
        <atik /><!--Atik-->
        <bar /><!--Bar300-->
        <faces /><!--Faces -->
      </div>
      <div class="grid sm:flex">
        <jhankaar /><!--Jhankaar club-->
        <kings /><!--kings Bull-->
        <xoyo /><!--xoyo-->

      </div>
    </div>
    <br />
  </Layout>
</template>

<script>
import atik from "@/components/Nightclubs/atik";
import bar from "@/components/Nightclubs/bar";
import faces from "@/components/Nightclubs/faces";
import jhankaar from "@/components/Nightclubs/jhankaar";
import kings from "@/components/Nightclubs/kings";
import xoyo from "@/components/Nightclubs/xoyo";

import date from "@/components/Home/date";

export default {
  metaInfo: {
    title: "Nightclubs",
    meta : [
      {
        name   : "description",
        content: 
          "Visit Places Of Historical And Local Interest In East London for Day Out."
      }
    ]
  },
  components: {
    atik,
    bar,
    faces,
    jhankaar,
    kings,
    xoyo,
    date
  }
};
</script>
