<template>
  <div
    class="
      heros
      bg-white
      d-flex
      justify-content-center
      align-items-center
      flex-column
      w-100
    "
  >
    <div class="platform-landing__title d-flex justify-content-center">
      其他未服務內容
    </div>
    <div class="platform-landing__sub-title">
      基於人員與客戶安全、隱私等考量
    </div>
    <div
      class="
        platform-landing__wrapper
        d-flex
        justify-content-evenly
        align-items-center
        flex-column flex-md-row
        w-100
        mt-3
      "
    >
      <div class="addition_listgroup">
        <div class="addition__list">
          <fa :icon="['fas', 'circle']" />
          移動或抬起超過10公斤的大型家具或重物
        </div>
        <div class="addition__list">
          <fa :icon="['fas', 'circle']" />
          天花板、高處窗戶及可觸及範圍外的表面清潔
        </div>
        <div class="addition__list">
          <fa :icon="['fas', 'circle']" />
          危險性外窗清潔及窗簾、紗窗清洗
        </div>
        <div class="addition__list">
          <fa :icon="['fas', 'circle']" />
          天花板、高處窗戶及可觸及範圍外的表面清潔
        </div>
        <div class="addition__list">
          <fa :icon="['fas', 'circle']" />
          危險化學物質處理
        </div>
        <div class="addition__list">
          <fa :icon="['fas', 'circle']" />
          裝潢後細清(粉塵清潔)
        </div>
      </div>

      <div class="addition_listgroup">
        <div class="addition__list">
          <fa :icon="['fas', 'circle']" />
          移動或抬起超過10公斤的大型家具或重物
        </div>
        <div class="addition__list">
          <fa :icon="['fas', 'circle']" />
          天花板、高處窗戶及可觸及範圍外的表面清潔
        </div>
        <div class="addition__list">
          <fa :icon="['fas', 'circle']" />

          危險性外窗清潔及窗簾、紗窗清洗
        </div>
        <div class="addition__list">
          <fa :icon="['fas', 'circle']" />
          天花板、高處窗戶及可觸及範圍外的表面清潔
        </div>
        <div class="addition__list">
          <fa :icon="['fas', 'circle']" />
          危險化學物質處理
        </div>
        <div class="addition__list">
          <fa :icon="['fas', 'circle']" />
          裝潢後細清(粉塵清潔)
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Heros",
};
</script>

<style scoped>
.heros {
  background-color: #f5f3f4;
  padding: 40px 0 30px;
}

.platform-landing__title {
  font-size: 32px;
  color: #3e4459;
  font-weight: 500;
  margin-bottom: 8px;
}

.platform-landing__sub-title {
  margin-bottom: 20px;
  font-weight: 300;
  color: #c9302c;
}

.addition__list {
  font-size: 14px;
}
</style>
