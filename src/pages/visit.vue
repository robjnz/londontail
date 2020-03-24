<template>
  <Layout>
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-16 text-4xl text-red-600">
        <span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        Places to Visit
      </h1>
      <!--<date class="ml-8" />-->
      <br />

      <div class="grid sm:flex">
        <bexley /><!--bexleyWoods-->
        <chingford /><!--Chingford Sky Trail-->
        <docklands /><!--Docklands Museum-->
      </div>
      <div class="grid sm:flex">
        <eastbury /><!--Eastbury Manor House-->
        <elizabeth /><!--Elizabeth's Hunting Lodge-->
        <eltham /><!--Eltham Palace-->
      </div>
      <div class="grid sm:flex">
        <epping /><!--Epping Forest-->
        <fairlop /><!--Fairlop Waters Park-->
        <geffrye /><!--Geffrye Museum-->
      </div>
      <div class="grid sm:flex">
        <hackney /><!--Hackney City Farm-->
        <hall /><!--Hall Place & Gardens-->
        <havering /><!--Havering Country Park-->
      </div>
       <div class="grid sm:flex">
        <horniman/><!--Horniman Museam & Park-->
        <hospital /><!--Hospital Chapel Ilford-->
        <house /><!--House Mill-->
      </div>
       <div class="grid sm:flex">
        <jack /><!--Jack The Ripper Museum-->
        <lee /><!--Lee Valley-->
        <mayesbrook /><!--Mayesbrook Park-->
      </div>
      <div class="grid sm:flex">
        <mudchute /><!--mudchute-->
        <newham /><!--Newham City Farm-->
        <queen /><!--Queen Elizabeth Olympic Park-->
      </div>
      <div class="grid sm:flex">
        <ragged /><!--Ragged School Museum-->
        <rainham /><!--Rainham Hall-->
        <ranger /><!--Ranger’s House-->
      </div>
       <div class="grid sm:flex">
        <red /><!--Red house-->
        <greenwich /><!--Royal Museums Greenwich-->
        <severndroog /><!--Severndroog Castle-->
      </div>
      <div class="grid sm:flex">
        <antioch /><!--St. Margaret of Antioch-->
        <sutton /><!--Sutton House-->
        <thames /><!--Thames Barrier-->
      </div>
      <div class="grid sm:flex">
        <tower /><!--Tower Of London-->
        <trinity /><!--Trinity Buoy Wharf-->
        <upminster /><!--Upminster Windmill-->
      </div>
       <div class="grid sm:flex">
        <valence /><!--Valence House Museum-->
        <valentines /><!--Valentines Mansion-->
        <victoria /><!--Victoria Park-->
      </div>
       <div class="grid sm:flex">
        <viktor /><!--Viktor Wyne Museum-->
        <wanstead /><!--Wansted Park-->
        <william /><!--William Morris Gallery-->
      </div>

      <div class="grid sm:flex">
        <bethune /><!--Bethune Nature reserve-->
        <totteridge /><!--Totteridge fields-->
       
      </div>
    </div>
    <br />
  </Layout>
</template>

<script>
import antioch from "@/components/Visit/antioch";
import bexley from "@/components/Visit/bexley";
import chingford from "@/components/Visit/chingford";
import danson from "@/components/Visit/danson";
import docklands from "@/components/Visit/docklands";
import eastbury from "@/components/Visit/eastbury";
import elizabeth from "@/components/Visit/elizabeth";
import eltham from "@/components/Visit/eltham";
import epping from "@/components/Visit/epping";
import fairlop from "@/components/Visit/fairlop";
import greenwich from "@/components/Visit/greenwich";
import geffrye from "@/components/Visit/geffrye";
import hackney from "@/components/Visit/hackney";
import hall from "@/components/Visit/hall";
import havering from "@/components/Visit/havering";
import horniman from "@/components/Visit/horniman";
import hospital from "@/components/Visit/hospital";
import house from "@/components/Visit/house";
import jack from "@/components/Visit/jack";
import lee from "@/components/Visit/lee";
import mayesbrook from "@/components/Visit/mayesbrook";
import mudchute from "@/components/Visit/mudchute";
import newham from "@/components/Visit/newham";
import queen from "@/components/Visit/queen";
import ragged from "@/components/Visit/ragged";
import rainham from "@/components/Visit/rainham";
import ranger from "@/components/Visit/ranger";
import red from "@/components/Visit/red";
import severndroog from "@/components/Visit/severndroog";
import sutton from "@/components/Visit/sutton";
import thames from "@/components/Visit/thames";
import tower from "@/components/Visit/tower";
import trinity from "@/components/Visit/trinity";
import upminster from "@/components/Visit/upminster";
import valence from "@/components/Visit/valence";
import valentines from "@/components/Visit/valentines";
import victoria from "@/components/Visit/victoria";
import viktor from "@/components/Visit/viktor";
import wanstead from "@/components/Visit/wanstead";
import william from "@/components/Visit/william";
import totteridge from "@/components/Visit/totteridge";
import bethune from "@/components/Visit/bethune";


import date from "@/components/Home/date";

export default {
  metaInfo: {
    title: "Visit",
    meta : [
      {
        name   : "description",
        content: "Visit Places Of Historical And Local Interest In East London for Day Out."
      }
    ]
  },
  components: {
    antioch,
    bethune,
    bexley,
    chingford,
    danson,
    docklands,
    eastbury,
    elizabeth,
    eltham,
    epping,
    fairlop,
    greenwich,
    geffrye,
    hackney,
    hall,
    havering,
    horniman,
    hospital,
    house,
    jack,
    lee,
    mayesbrook,
    mudchute,
    newham,
    queen,
    ragged,
    rainham,
    ranger,
    red,
    severndroog,
    sutton,
    thames,
    totteridge,
    tower,
    trinity,
    upminster,
    valence,
    valentines,
    victoria,
    viktor,
    wanstead,
    william,
    date
  }
};
</script>
