<template>
  <body>
    <div class="platform-landing__wrapper">
      <div
        class="
          recommend-cleaner
          d-flex
          justify-content-between
          align-items-center
          w-100
        "
      >
        <!-- Clean-feature section -->
        <div
          class="
            recommend-cleaner__feature
            d-flex
            justify-content-center
            align-items-center
            flex-column
            w-50
          "
        >
          <div class="feature__title-wrapper">
            <div class="feature__title">全台唯一</div>
            <div class="feature__sub-title">挑人員，評價直接看！</div>
          </div>

          <div
            class="
              feature__info
              d-flex
              justify-content-evenly
              align-items-center
              w-100
            "
          >
            <div class="feature__info-each text-center">
              <img
                width="110"
                height="110"
                class="res-img"
                style="opacity: 1; transition: opacity 0.5s ease 0s"
                src="../assets/images/part2_advantage1 copy.png"
              />
              <div class="feature__info-text">人員具良民證、<br />清潔證照</div>
            </div>
            <div class="feature__info-each text-center">
              <img
                width="110"
                height="110"
                class="res-img"
                style="opacity: 1; transition: opacity 0.5s ease 0s"
                src="../assets/images/part2_advantage2 copy.png"
              />
              <div class="feature__info-text">
                今天訂明天掃，<br />即時預約超方便
              </div>
            </div>
            <div class="feature__info-each text-center">
              <img
                width="110"
                height="110"
                class="res-img"
                style="opacity: 1; transition: opacity 0.5s ease 0s"
                src="../assets/images/part2_advantage3 copy.png"
              />
              <div class="feature__info-text">
                價錢、履歷、評價 <br />透明公開
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Recommend-Cleaner section -->
    </div>
  </body>
</template>

<script>
export default {
  name: "Members",
};
</script>

<style scoped>
body {
  font-family: "pingfang tc", "microsoft jhenghei", "microsoft yahei",
    "Helvetica Neue", Helvetica, Arial, sans-serif;
  line-height: 1.5;
  min-height: 100%;
  color: #3e4459;
  background-color: #f5f3f4;
}

.platform-landing__wrapper {
  display: flex;
  align-items: center;
  flex-direction: column;
  width: 100%;
  background-color: #f5f3f4;
  padding: 40px 0 30px 0;
}

.feature__title-wrapper {
  padding: 0 36px 16px;
  text-align: center;
  border-bottom: 2px solid #3e4459;
  margin-bottom: 24px;
}

.feature__title {
  font-size: 72px;
}

.feature__sub-title {
  font-size: 36px;
}
</style>
