<!-- Please remove this file from your project -->
<template>
  <body>
    <div class="platform-landing__wrapper border">
      <div
        class="
          platform-landing__title
          d-flex
          justify-content-center
          align-items-center
        "
      >
        <img
          src="https://storage.googleapis.com/jackercleaning/assets/optImg/icon/part1_icon.png"
          width="24"
          height="24"
          alt="clean icon"
          class="title-icon"
        />
        鐘點清潔會掃哪裡?時數怎麼算?
      </div>
      <div class="platform-landing__sub-title text-center">
        可以根據自己的需求查看會清潔的細項，並預估總共需要的時數，當天清潔人員會再討論狀況做些調整！
      </div>
      <div class="platform-landing__body landing-service w-100">
        <!-- TimeOut-button -->
        <div class="landing-service__action d-flex justify-content-center">
          <button class="landing-service__action timeout-btn d-inline-block">
            時數計算教學
          </button>
        </div>

        <!-- Product-Card Section-Web -->
        <div class="d-none d-md-block">
          <ProductCard />
        </div>

        <!-- Product-Card Section-Mobile -->
        <div class="d-block d-md-none">
          <ProductCardMob />
        </div>

        <!-- Reserve-button -->
        <div
          class="landing-service__action d-flex justify-content-center w-100"
        >
          <button class="landing-service__action reserve-btn d-inline-block">
            開始預約
            <span>
              <fa :icon="['fas', 'angle-right']" />
            </span>
          </button>
        </div>
      </div>
      <!-- Heros Section -->
      <Heros />
      <!-- Cleaners Section -->
      <Cleaners />
      <!-- Reserve-button -->
      <div class="d-block d-md-none">
        <div
          class="landing-service__action d-flex justify-content-center w-100"
        >
          <button class="landing-service__action reserve-btn d-inline-block">
            開始預約
            <span>
              <fa :icon="['fas', 'angle-right']" />
            </span>
          </button>
        </div>
      </div>
    </div>
  </body>
</template>

<script>
import Heros from "./Heros.vue";
import Cleaners from "./Cleaners.vue";
import ProductCard from "./ProductCard.vue";
import ProductCardMob from "./ProductCardMob.vue";
export default {
  name: "Platform",
  components: { Heros, Cleaners, ProductCard, ProductCardMob },
};
</script>

<style scoped>
body {
  background-color: #f5f3f4;
}

.platform-landing__body {
  padding-bottom: 40px;
}

.platform-landing__title {
  font-size: 18px;
  color: #3e4459;
  font-weight: 500;
  margin-bottom: 8px;
  padding-top: 40px;
}

@media (min-width: 768px) {
  .platform-landing__title {
    font-size: 32px;
  }
}

.platform-landing__sub-title {
  font-weight: 300;
  margin-bottom: 20px;
  padding: 0 16px;
}

.landing-service__action .timeout-btn {
  padding: 6px 12px;
  font-size: 14px;
  font-weight: 400;
  outline: 0;
  background: #fff;
  color: #36bbd9;
  border: 1px solid #36bbd9;
  border-radius: 4px;
  cursor: pointer;
}

.landing-service__action .timeout-btn:hover {
  color: #fff;
  background-color: #36bbd9;
}

.landing-service__action .reserve-btn {
  display: inline-block;
  padding: 4px 90px;
  font-size: 14px;
  font-weight: 400;
  outline: 0;
  background: #36bbd9;
  color: #fff;
  border: 1px solid transparent;
  border-radius: 4px;
  cursor: pointer;
  text-align: center;
}

.landing-service__action .reserve-btn:hover {
  color: #fff;
  background-color: #239db9;
}
</style>
