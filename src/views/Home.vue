<template>
  <div class="home">
    <hero-cmp />
    <!-- stay -->
    <experience />
    <menu-highlights-cmp />
    <events-cmp />
    <ready-cmp />
    <app-footer />
  </div>
</template>

<script>
// @ is an alias to /src
import appHeader from "../cmps/app-header.vue";
import heroCmp from "../cmps/hero-cmp.vue";
import featuresCmp from "../cmps/features-cmp.vue";
import menuHighlightsCmp from "../cmps/menu-highlights-cmp.vue";
import readyCmp from "../cmps/ready-cmp.vue"
import appFooter from "../cmps/app-footer.vue";
import eventsCmp from "../cmps/events-cmp.vue"
import experience from "../cmps/experience.vue"



export default {
  name: 'Home',
  components: {
    appHeader,
    heroCmp,
    featuresCmp,
    menuHighlightsCmp,
    appFooter,
    readyCmp,
    eventsCmp,
    experience,
  }
}
</script>
