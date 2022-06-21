<!-- Please remove this file from your project -->
<template>
  <body>
    <div class="banner">
      <div class="header-inner">
        <div class="header-search-container">
          <div class="header-search-title">
            預約居家清潔，快篩PASS人員安心選!!
            <br />
            <div class="header-search-title--sub">
              潔客已完成COVID-19篩檢，可預約人員皆為「快篩陰性」
            </div>
          </div>
          <Tabs />
        </div>
      </div>
    </div>
  </body>
</template>

<script>
import Tabs from "./Tabs.vue";
export default {
  name: "Banner",
  components: { Tabs },
};
</script>

<style scoped>
/* global color setting */
body {
  font-family: "pingfang tc", "microsoft jhenghei", "microsoft yahei",
    "Helvetica Neue", Helvetica, Arial, sans-serif;
  line-height: 1.5;
  min-height: 100%;
  color: #3e4459;
}

.banner {
  background-image: url("../assets/images/banner.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  height: 600px;
}

.header-inner {
  max-width: 1200px;
  margin: auto;
}

.header-search-container {
  max-width: 585px;
  width: 50%;
  padding: 20px;
  margin: 5px auto 0;
  text-align: center;
}

.header-search-title {
  color: #3e4459;
  font-weight: 700;
  font-size: 28px;
  margin-bottom: 50px;
  letter-spacing: 3px;
}

.header-search-title--sub {
  font-size: 14px;
}
</style>
