<template>
  <div class="m-4 mt-1 p-4 w-auto rounded-lg">
    <div class="p-6">
      <h2 class="text-3xl text-blue-500">
        <span>
          <i class="fas fa-landmark"></i>
        </span>
        Places to Visit
      </h2>
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sat 14 March
      </h3>
      <!-- Fri 13 March to Fri 3 Apri-->
      <div class="grid sm:flex">
        <queen /><!--olympic park-->
        <valentines /><!--valentines-->
      </div>
      <!--wed 18 march-->

      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Wed 18 March
      </h3>

      <div class="grid sm:flex"><docklands /><!--Docklands Museum --></div>

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

      <!--27 march -->
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Fri 27 March
      </h3>
      <div class="grid sm:flex"><valence /><!--Valence House Museum--></div>

      <!--april-->
      <!--4 april-->
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        Sat 4 April
      </h3>
      <div class="grid sm:flex">
        <eltham /><!-- Eltham Palace-->
        <red /><!-- red house-->
      </div>

      <!--23 april-->
      <h3 class="text-xl text-pink-300">
        <span style="font-size: 1em;">
          <i class="far fa-calendar-alt"></i>
        </span>
        thurs 23 April
      </h3>
      <div class="grid sm:flex"><trinity /><!-- Trinity Buoy Wharf--></div>

      <g-link class="text-blue-500 text-2xl hover:text-white" to="/visit"
        >Places to visit</g-link
      >
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
import date from "@/components/Home/date";

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
    date
  }
};
</script>
