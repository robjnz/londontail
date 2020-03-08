<template>
  <Layout>
    <div class="container-md m-12">
      <h1 class="text-4xl text-red-700">What on in East London</h1>
      <date />
      <br />
      <div class="port container" id="works">
        <on />

        <br />
        <theatre />
        <br />
        <night />
        <br />
        <!--
            <inst />
            -->
      </div>

      <div class="port container">
        <div class="grid grid-cols-2 gap-4">
          <div id="works">
            <football />
          </div>

          <div id="works">
            <series />
            <br />
            <film />
          </div>
        </div>
      </div>
    </div>

    <p class="font-sans m-3 p-4 text-1xl text-left bg-red-900 text-red-400 ">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cum a explicabo
      praesentium odit fuga sequi voluptatibus placeat, obcaecati provident eius
      id commodi culpa consequatur? Voluptatibus odit nulla aliquid iusto ipsam!
    </p>

   
    <div
      class = "m-2 p-6 bg-blue-900 text-blue-200 border-4 border-red-900 rounded-full"
    >
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam suscipit
        orci ac nisl varius varius. Nullam auctor finibus pulvinar. Morbi
        porttitor placerat enim nec consequat.
      </p>
      <p class="mt-3 text-gray-400">
        - Victor Gonzalez, <span class="italic">instructor</span>
      </p>
    </div>
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
}
.home-links a {
  margin-right: 1rem;
}
</style>
