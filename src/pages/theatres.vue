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
      
      <div class="grid sm:flex">
        <hoxton /><!--Hoxton Hall-->
        <ilford /><!--Kenneth More Theatre-->
        <hornchurch/><!--Queen's Theatre Hornchurch -->
      </div>
      
      <div class="grid sm:flex">
        <hoxton /><!--Hoxton Hall-->
        <ilford /><!--Kenneth More Theatre-->
        <hornchurch /><!--Queen's Theatre Hornchurch -->
      </div>
     
    </div>
    <br />
  </Layout>
</template>

<script>
import barking from "@/components/Theatres/barking";
import greenwich from "@/components/Theatres/greenwich";
import hackney from "@/components/Theatres/hackney";
import hoxton from "@/components/Theatres/hoxton";
import ilford from "@/components/Theatres/ilford";
import hornchurch from "@/components/Theatres/hornchurch";



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
    hornchurch,
    hoxton,
    ilford,
    
    
    date,
  }
};
</script>

<style></style>
