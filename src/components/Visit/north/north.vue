<template>
<div>
    <h2 class="ml-8 text-3xl text-blue-200">
        North London
      </h2>
      <div class="grid sm:flex">
        <bethune /><!--Bethune Nature reserve-->
        <stephens /><!--Stephens house-->
        <totteridge /><!--Totteridge fields-->
      </div>

      <div class="grid sm:flex">
        <airforce /><!--Royal Air Force Museum-->
       
      </div>
    </div>

</template>

<script>

import bethune from "@/components/Visit/bethune";
import stephens from "@/components/Visit/stephens";
import airforce from "@/components/Visit/airforce";
import totteridge from "@/components/Visit/totteridge";

export default {
    components: {
      bethune,
        stephens,
        totteridge,
        airforce,
    }
}
</script>

