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
        <greenwich /><!--Greenwich Theatre-->
        <hackney /><!--Faces -->
      </div>
    </div>
    <br />
  </Layout>
</template>

<script>
import barking from "@/components/Theatres/barking";
import greenwich from "@/components/Theatres/greenwich";
import hackney from "@/components/Theatres/hackney";

import ilford from "@/components/Theatres/ilford";
import romford from "@/components/Theatres/romford";

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
        content: "Whats on guide for Local Theatres In East London."
      }
    ]
  },
  components: {
    barking,
    greenwich,
    hackney,
    ilford,
    romford,
    bar,
    faces,
    jhankaar,
    kings,
    xoyo,
    date
  }
};
</script>

<style></style>
