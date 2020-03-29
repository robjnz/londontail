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
        <alex /><!--alexandra palace-->
        <arts /><!--artsdepot-->
        <barking /><!--Broadway Theatre Barking-->
       </div>
      
      <div class="grid sm:flex">
        <chickenshed /><!--chickenshed-->
        <greenwichT /><!--Greenwich Theatre-->
        <hackneyT /><!--hackney empire -->
      </div>
      
      <div class="grid sm:flex">
        <hoxton /><!--Hoxton Hall-->
        <intimate /><!--Intimate Theatre-->
        <ilford /><!--Kenneth More Theatre-->
      </div>
      
      <div class="grid sm:flex">
        <hornchurch/><!--Queen's Theatre Hornchurch -->
        <rainbow /><!--Rainbow Theatre-->
        <stratford /><!--Theatre Royal Stratford East-->
      </div>
      <div class="grid sm:flex">
        <two /><!--The O2 arena-->
        <wilton /><!--Wilton's Music Hall -->
        <yard/><!--The Yard -->
      </div>
     
    </div>
    <br />
  </Layout>
</template>

<script>
import barking from "@/components/Theatres/barking";
import greenwichT from "@/components/Theatres/greenwichT";
import hackneyT from "@/components/Theatres/hackneyT";
import hoxton from "@/components/Theatres/hoxton";
import ilford from "@/components/Theatres/ilford";
import hornchurch from "@/components/Theatres/hornchurch";
import stratford from "@/components/Theatres/stratford";
import two from "@/components/Theatres/two";
import wilton from "@/components/Theatres/wilton";
import yard from "@/components/Theatres/yard";
import arts from "@/components/Theatres/arts";
import chickenshed from "@/components/Theatres/chickenshed";
import alex from "@/components/Theatres/alex";
import intimate from "@/components/Theatres/intimate";
import rainbow from "@/components/Theatres/rainbow";



import date from "@/components/Home/date";

export default {
  metaInfo: {
    title: "Theatres",
    meta : [
      {
        name   : "description",
        content: "Whats on guide for Local Theatres In North And East London."
      }
    ]
  },
  components: {
    barking,
    greenwichT,
    hackneyT,
    hornchurch,
    hoxton,
    ilford,
    stratford,
    two,
    wilton,
    yard,
    arts,
    chickenshed,
    alex,
    intimate,
    rainbow,
    date,
  }
};
</script>

<style></style>
