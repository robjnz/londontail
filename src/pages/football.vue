<template>
  <Layout>
    <div id="background" class="container ml-8">
      <h1 class="ml-8 mt-16 text-4xl text-red-600">
        <span class="text-pink-300">
          <i class="fas fa-futbol"></i>
        </span>
        Football
      </h1>
      <!--<date class="ml-8" />-->
      <br />

      <div class="grid sm:flex">
        <barkingF /><!--Barking-->
        <barkingside /><!--Barkingside-->
        <bexley /><!--Bexley-->
      </div>

       <div class="grid sm:flex">
        <bridon /><!--Bridon Ropes-->
        <canning /><!--Canning Town-->
        <charlton /><!--charlton-->
      </div>

        <div class="grid sm:flex">
        <bridon /><!--Bridon Ropes-->
        <canning /><!--Canning Town-->
        <charlton /><!--charlton-->
       
      </div>
    </div>

    <br />
  </Layout>
</template>

<script>
import barkingF from "@/components/Football/barkingF";
import barkingside from "@/components/Football/barkingside";
import bexley from "@/components/Football/bexley";
import bridon from "@/components/Football/bridon";
import canning from "@/components/Football/canning";
import charlton from "@/components/Football/charlton";




export default {
  metaInfo: {
    title: "Football",
    meta : [
      {
        name   : "description",
        content: "Whats on guide for Local football matches In East London."
      }
    ]
  },
  components: {
    barkingF,
    barkingside,
    bexley,
    bridon,
    canning,
    charlton,
  }
};
</script>
