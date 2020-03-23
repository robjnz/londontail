<template>
  <Layout>
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-16 text-4xl text-red-600">
        <span class="text-pink-300">
          <i class="fas fa-football-ball"></i>
        </span>
        Rugby
      </h1>
      <!--<date class="ml-8" />-->
      <br />

      <div class="grid sm:flex">
        <barkingR /><!--Barking Rugby-->
        <blackheath /><!--Blackheath Rugby-->
        <blackheathwomen /><!--Blackheathwomen rugby-->
      </div>

    </div>

    <br />
  </Layout>
</template>

<script>
import barkingR from "@/components/Rugby/barkingR";
import blackheath from "@/components/Rugby/blackheath";
import blackheathwomen from "@/components/Rugby/blackheathwomen";

import date from "@/components/Home/date";

export default {
  metaInfo: {
    title: "Rugby",
    meta : [
      {
        name   : "description",
        content: "Whats on guide for rugby home matches In East London."
      }
    ]
  },
  components: {
    barkingR,
    blackheath,
    blackheathwomen,
    date
  }
};
</script>
