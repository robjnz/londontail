<template>
  <div class="m-4 mt-1 p-4 w-auto rounded-lg">
    <div class="p-6">
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Thurs 19 March
      </h3>

      <div class="grid sm:flex">
        
        <queen /><!--olympic park-->
        <valentines /><!--valentines-->
      </div>
      <div class="grid sm:flex">
        <barking /><!--barking-->
        <hornchurch /><!--romford-->
        
      </div>

      <div class="grid sm:flex"></div>
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Fri 20 March
      </h3>
      <div class="grid sm:flex"><atik /><!--atik--></div>
      <br />
      <!--sat 21 march-->
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sat 21 March
      </h3>

      <div class="grid sm:flex">
        <severndroog /><!--Severndroog Castle-->
        <sutton /><!--sutton house-->
      </div>
      <div class="grid sm:flex">
        <hoxton /><!--hoxton-->
        <barkingF /><!--Barking F C-->
      </div>
      <!-- 22 March-->
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sun 22 March
      </h3>
      <div class="grid sm:flex">
        <eastbury /><!--Eastbury Manor House-->
        <hall /><!--Hall Place & Gardens-->
        <rainham /><!--rainham hall-->
      </div>
      <div class="grid sm:flex">
        <charltonwomen/><!--charltonwomen-->
        
      </div>
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Tues 24 March
      </h3>
      <div class="grid sm:flex"><stratford /><!--stratford--></div>

      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Wed 25 March
      </h3>
      <div class="grid sm:flex"><wilton /><!--wilton--></div>

      <!--27 march-->
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Fri 27 March
      </h3>
      <div class="grid sm:flex">
        <valence /><!--Valence House Museum-->
        <two /><!--02-->
        <xoyo /><!--xoyo-->
      </div>

      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Mon 30 March
      </h3>
      <div class="grid sm:flex"><barkingside /><!--barkingside fc--></div>

      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Wed 1 April
      </h3>
      <div class="grid sm:flex"><ilford /><!--ilford--></div>

      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Thurs 2 April
      </h3>
      <div class="grid sm:flex"><yard /><!--yard--></div>

      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Fri 3 April
      </h3>
      <div class="grid sm:flex"><faces /><!--faces--></div>

      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sat 4 April
      </h3>
      <div class="grid sm:flex">
        <eltham /><!-- Eltham Palace-->
        <red /><!--red house-->
        <charlton /><!--charlton fc-->
      </div>

       <div class="grid sm:flex">
        <dagred /><!--Dagenham & Redbridge-->
        <greenwichF /><!--greenwich fc-->
        <hornchurchF /><!--hornchurch fc-->
      </div>
 <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Fri 10 April
      </h3>
 <div class="grid sm:flex">
        <erithtown /><!--erith town fc-->
        
      </div>


      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sat 11 April
      </h3>
 <div class="grid sm:flex">
        <forest /><!--forest fc-->
      </div>

      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sat 18 April
      </h3>
      <div class="grid sm:flex">
        <ilfordF/><!-- ilford fc--></div>
    

      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Thurs 23 April
      </h3>
      <div class="grid sm:flex"><trinity /><!-- Trinity Buoy Wharf--></div>
    </div>
  </div>
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
import date from "@/components/Home/date";
import atik from "@/components/Nightclubs/atik";
import faces from "@/components/Nightclubs/faces";
import xoyo from "@/components/Nightclubs/xoyo";
import barkingF from "@/components/Football/barkingF";
import barkingside from "@/components/Football/barkingside";
import charlton from "@/components/Football/charlton";
import charltonwomen from "@/components/Football/charltonwomen";
import dagred from "@/components/Football/dagred";
import erithtown from "@/components/Football/erithtown";
import forest from "@/components/Football/forest";
import greenwichF from "@/components/Football/greenwichF";
import hornchurchF from "@/components/Football/hornchurchF";
import ilfordF from "@/components/Football/ilfordF";


export default {
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
    atik,
    faces,
    xoyo,
    barkingF,
    barkingside,
    charlton,
    charltonwomen,
    dagred,
    erithtown,
    forest,
    greenwichF,
    hornchurchF,
    ilfordF,
  }
};
</script>
