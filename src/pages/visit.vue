<template>
  <Layout>
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-16 text-4xl text-red-600">
        <span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        Places to Visit
      </h1>
      

      <div class="grid sm:flex">
        <alexandra /><!--alexandra palace-->
        <bethune /><!--Bethune Nature reserve-->
        <bexley /><!--bexleyWoods-->
      </div>
      <div class="grid sm:flex">
        <chingford /><!--Chingford Sky Trail-->
        <chislehurst /><!--Chislehurst Caves-->
        <churchhouse /><!--Church House Gardens-->
      </div>
      <div class="grid sm:flex">
        <minster /><!--Croydon Minster-->
        <crystalV /><!--Crystal Palace Park-->
        <deen /><!--DEEN CITY FARM-->
      </div>
      <div class="grid sm:flex">
        <down /><!--Down House-->
        <docklands /><!--Docklands Museum-->
        <eastbury /><!--Eastbury Manor House-->
         </div>
      <div class="grid sm:flex">
        <elizabeth /><!--Elizabeth's Hunting Lodge-->
        <eltham /><!--Eltham Palace-->
        <epping /><!--Epping Forest-->
 </div>
      <div class="grid sm:flex">
        <fairlop /><!--Fairlop Waters Park-->
        <fenton /><!--fenton house-->
        <forty /><!--forty hall-->
         </div>
      <div class="grid sm:flex">
        <freud /><!--Freud Museum-->
        <geffrye /><!--Geffrye Museum-->
        <hackney /><!--Hackney City Farm-->
         </div>
      <div class="grid sm:flex">
        <hall /><!--Hall Place & Gardens-->
        <havering /><!--Havering Country Park-->
        <horniman /><!--Horniman Museam & Park-->
         </div>
      <div class="grid sm:flex">
        <hospital /><!--Hospital Chapel Ilford-->
        <house /><!--House Mill-->
        <jack /><!--Jack The Ripper Museum-->
         </div>
      <div class="grid sm:flex">
        <jewish /><!--jewish museum-->
        <lee /><!--Lee Valley-->
        <canal /><!--London canal museum-->
         </div>
      <div class="grid sm:flex">
        <zoo /><!--london zoo-->
        <markfield /><!--Markfield -->
        <mayesbrook /><!--Mayesbrook Park-->
         </div>
      <div class="grid sm:flex">
        <morden /><!--MORDEN HALL PARK-->
        <mudchute /><!--mudchute-->
        <newham /><!--Newham City Farm-->
         </div>
      <div class="grid sm:flex">
        <queen /><!--Queen Elizabeth Olympic Park-->
        <ragged /><!--Ragged School Museum-->
        <rainham /><!--Rainham Hall-->
         </div>
      <div class="grid sm:flex">
        <ranger /><!--Ranger’s House-->
        <red /><!--Red house-->
        <airforce /><!--Royal Air Force Museum-->
         </div>
      <div class="grid sm:flex">
        <greenwich /><!--Royal Museums Greenwich-->
        <severndroog /><!--Severndroog Castle-->
        <shirley/><!--Shirley Windmill-->
         </div>
      <div class="grid sm:flex">
        <antioch /><!--St. Margaret of Antioch-->
        <stephens /><!--Stephens house-->
        <sutton /><!--Sutton House-->
         </div>
      <div class="grid sm:flex">
        <thames /><!--Thames Barrier-->
        <totteridge /><!--Totteridge fields-->
        <tower /><!--Tower Of London-->
         </div>
      <div class="grid sm:flex">
        <trinity /><!--Trinity Buoy Wharf-->
        <upminster /><!--Upminster Windmill-->
        <valence /><!--Valence House Museum-->
         </div>
      <div class="grid sm:flex">
        <valentines /><!--Valentines Mansion-->
        <victoria /><!--Victoria Park-->
        <viktor /><!--Viktor Wyne Museum-->
         </div>
      <div class="grid sm:flex">
        <wanstead /><!--Wansted Park-->
        <william /><!--William Morris Gallery-->
        <wimbledonmill /><!--Wimbledon Windmill-->
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

import alexandra from "@/components/Visit/north/alexandra";
import bethune from "@/components/Visit/north/bethune";
import canal from "@/components/Visit/north/canal";

import forty from "@/components/Visit/north/forty";
import jewish from "@/components/Visit/north/jewish";

import markfield from "@/components/Visit/north/markfield";

import stephens from "@/components/Visit/north/stephens";
import airforce from "@/components/Visit/north/airforce";
import totteridge from "@/components/Visit/north/totteridge";
import fenton from "@/components/Visit/north/fenton";
import zoo from "@/components/Visit/north/zoo";
import freud from "@/components/Visit/north/freud";
import down from "@/components/Visit/down";
import crystalV from "@/components/Visit/crystalV";
import chislehurst from "@/components/Visit/chislehurst";
import churchhouse from "@/components/Visit/churchhouse";
import shirley from "@/components/Visit/shirley";
import minster from "@/components/Visit/minster";
import morden from "@/components/Visit/morden";
import wimbledonmill from "@/components/Visit/wimbledonmill";
import deen from "@/components/Visit/deen";

import date from "@/components/Home/date";

export default {
  metaInfo: {
    title: "Visit",
    meta : [
      {
        name   : "description",
        content: 
          "Visit Places Of Historical And Local Interest In London for Day Out."
      }
    ]
  },
  components: {
    antioch,
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
    tower,
    trinity,
    upminster,
    valence,
    valentines,
    victoria,
    viktor,
    wanstead,
    william,
    alexandra,
    bethune,
    canal,
    forty,
    jewish,
    markfield,
    stephens,
    totteridge,
    airforce,
    fenton,
    zoo,
    freud,
    down,
    crystalV,
    chislehurst,
    churchhouse,
    shirley,
    minster,
    morden,
    wimbledonmill,
    deen,
    date,
  }
};
</script>
