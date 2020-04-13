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
        <battersea /><!--Battersea Park-->
        <batterseazoo /><!--Battersea Park Children’s Zoo-->
        </div>
      <div class="grid sm:flex">
        <bethune /><!--Bethune Nature reserve-->
        <bexley /><!--bexleyWoods-->
        <chingford /><!--Chingford Sky Trail-->
        </div>
      <div class="grid sm:flex">
        <chislehurst /><!--Chislehurst Caves-->
        <churchhouse /><!--Church House Gardens-->
        <minster /><!--Croydon Minster-->
        </div>
      <div class="grid sm:flex">
        <crystalV /><!--Crystal Palace Park-->
        <deen /><!--DEEN CITY FARM-->
        <demorgan /><!--De Morgan Center-->
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
         <emery /><!--Emery Walker’s House-->
        <fairlop /><!--Fairlop Waters Park-->
        <fenton /><!--fenton house-->
        </div>
      <div class="grid sm:flex">
        <forty /><!--forty hall-->
        <freud /><!--Freud Museum-->
        <geffrye /><!--Geffrye Museum-->
        </div>
      <div class="grid sm:flex">
        <hackney /><!--Hackney City Farm-->
        <hall /><!--Hall Place & Gardens-->
        <havering /><!--Havering Country Park-->
        </div>
      <div class="grid sm:flex">
        <robinson /><!--HEATH ROBINSON MUSEUM-->
        <horniman /><!--Horniman Museam & Park-->
        <hospital /><!--Hospital Chapel Ilford-->
        </div>
      <div class="grid sm:flex">
        <house /><!--House Mill-->
        <jack /><!--Jack The Ripper Museum-->
        <jewish /><!--jewish museum-->
        </div>
      <div class="grid sm:flex">
        <kew /><!--Kew Gardens -->
        <lee /><!--Lee Valley-->
        <canal /><!--London canal museum-->
        </div>
      <div class="grid sm:flex">
        <zoo /><!--london zoo-->
        <marblehouse /><!--MARBLE HILL HOUSE -->
        <markfield /><!--Markfield -->
        </div>
      <div class="grid sm:flex">
        <mayesbrook /><!--Mayesbrook Park-->
        <morden /><!--MORDEN HALL PARK-->
        <mudchute /><!--mudchute-->
        </div>
      <div class="grid sm:flex">
        <newham /><!--Newham City Farm-->
        <queen /><!--Queen Elizabeth Olympic Park-->
        <pitzhanger /><!--Pitzhanger Manor House-->
        </div>
      <div class="grid sm:flex">
        <ragged /><!--Ragged School Museum-->
        <rainham /><!--Rainham Hall-->
        <ranger /><!--Ranger’s House-->
        </div>
      <div class="grid sm:flex">
        <red /><!--Red house-->
        <roundwood /><!--Roundwood Park-->
        <airforce /><!--Royal Air Force Museum-->
        </div>
      <div class="grid sm:flex">
        <greenwich /><!--Royal Museums Greenwich-->
        <ruislip /><!--Ruislip Woods -->
        <severndroog /><!--Severndroog Castle-->
        </div>
      <div class="grid sm:flex">
        <shirley/><!--Shirley Windmill-->
        <antioch /><!--St. Margaret of Antioch-->
        <stephens /><!--Stephens house-->
        </div>
      <div class="grid sm:flex">
        <sutton /><!--Sutton House-->
        <thames /><!--Thames Barrier-->
        <totteridge /><!--Totteridge fields-->
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
        <wandsworthcommon /><!--Wandsworth Common-->
        <wanstead /><!--Wansted Park-->
        </div>
      <div class="grid sm:flex">
        <william /><!--William Morris Gallery-->
        <wimbledoncommon /><!--Wimbledon Common-->
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
import wimbledoncommon from "@/components/Visit/wimbledoncommon";
import wandsworthcommon from "@/components/Visit/wandsworthcommon";
import demorgan from "@/components/Visit/demorgan";
import batterseazoo from "@/components/Visit/batterseazoo";
import battersea from "@/components/Visit/battersea";
import roundwood from "@/components/Visit/roundwood";
import pitzhanger from "@/components/Visit/pitzhanger";
import emery from "@/components/Visit/emery";
import robinson from "@/components/Visit/robinson";
import ruislip from "@/components/Visit/ruislip";
import marblehouse from "@/components/Visit/marblehouse";
import kew from "@/components/Visit/kew";


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
    wimbledoncommon,
    wandsworthcommon,
    demorgan,
    batterseazoo,
    battersea,
    roundwood,
    pitzhanger,
    emery,
    robinson,
    ruislip,
    marblehouse,
    kew,
    date,
  }
};
</script>
