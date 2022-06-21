<template>
  <div class="Home">
    <Header />
    <Banner />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Header from "@/components/Header.vue";
import Banner from "@/components/Banner.vue";

export default Vue.extend({
  name: "IndexPage",
  components: {
    Header,
    Banner,
  },
});
</script>

