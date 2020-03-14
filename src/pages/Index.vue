<template>
  <Layout>
    <div id="background" class="container m-auto">
      <h1 class="ml-12 mt-16 text-4xl text-red-600">What's on in East London</h1>
      <!--<date class="ml-8"/>-->
      <on />
      <br />

      <theatre />
      <br />
      <night />

    </div>
    <br />
  </Layout>
</template>

<script>
import football from "@/components/Home/football";
import series from "@/components/Home/series";
import inst from "@/components/Home/inst";
import on from "@/components/Home/on";
import film from "@/components/Home/film";
import theatre from "@/components/Home/theatre";
import night from "@/components/Home/night";
import date from "@/components/Home/date";

export default {
  metaInfo: {
    title: "London East",
    meta : [
      {
        name   : "description",
        content: 
          "What’s on today in east London the local cinemas, theatres, nightclubs & football matches, free online movies, tv series, picard, places to visit for days out in east London, places to eat, job search resources and much more!"
      }
    ],
    script: [
      { scr: "https: //cdn.jsdelivr.net/npm/gsap@3.0.4/dist/gsap.min.js" },
      { src: "https://cdn.jsdelivr.net/npm/jquery@3.4.1/dist/jquery.min.js" },
      { src: "https://cdn.jsdelivr.net/npm/animejs@3.1.0/lib/anime.min.js" },
      { src: "https://kit.fontawesome.com/e3c70d4fc5.js" }
    ]
  },
  components: {
    football,
    series,
    inst,
    on,
    film,
    theatre,
    night,
    date
  }
};
</script>

<style>
.Hero {
  padding-top   : 10rem;
  padding-bottom: 10rem;
  background    : darksalmon;
  color         : #337;
}
.Port {
  padding: 5rem;
}
.work {
  padding: 2rem 1rem;
}
.work-card {
  box-shadow   : 0px 0px 20px rgba(0, 0, 0.1);
  padding      : 1rem;
  border-radius: 0.2rem;
  color        : #00ff7f;
  margin       : 1rem;
}

.home-links a {
  margin-right: 1rem;
}
</style>
