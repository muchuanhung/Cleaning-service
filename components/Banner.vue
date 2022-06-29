<!-- Please remove this file from your project -->
<template>
  <div class="banner">
    <div class="header-inner mx-auto">
      <div class="header-search-container mx-auto text-center">
        <div class="header-search-title text-start text-md-center">
          <h1 class="d-none d-md-block">預約居家清潔，三分鐘馬上搞定！</h1>
          <h1 class="d-block d-md-none">
            預約居家清潔，<br />三分鐘馬上搞定！
          </h1>
        </div>
        <ReserveForm />
      </div>
    </div>
  </div>
</template>

<script>
import ReserveForm from "./ReserveForm.vue";
export default {
  name: "Banner",
  components: { ReserveForm },
};
</script>

<style scoped>
.banner {
  background-image: url("https://i.imgur.com/SXh2bmj.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  height: 600px;
  padding-top: 50px;
}

.header-inner {
  max-width: 1200px;
}

.header-search-container {
  max-width: 585px;
  padding: 20px;
}

.header-search-title {
  color: #3e4459;
  font-weight: 700;
  font-size: 28px;
  margin-bottom: 50px;
  letter-spacing: 3px;
}

@media (min-width: 768px) {
  .banner {
    background-image: url("https://i.imgur.com/oGr4dPm.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    height: 600px;
  }
}
</style>
