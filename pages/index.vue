<template>
  <div class="home">
    <Header />
    <Banner />
    <Platform />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Header from "@/components/Header.vue";
import Banner from "@/components/Banner.vue";
import Platform from "~/components/Platform.vue";

export default Vue.extend({
  name: "IndexPage",
  components: {
    Header,
    Banner,
    Platform,
  },
});
</script>

<style scoped>
/* RESET */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
.home {
  font-family: "pingfang tc", "microsoft jhenghei", "microsoft yahei",
    "Helvetica Neue", Helvetica, Arial, sans-serif;
  line-height: 1.5;
  min-height: 100%;
  color: #3e4459;
  background-color: #f5f3f4;
}
</style>

