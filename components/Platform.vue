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
        <div class="landing-service__action d-flex justify-content-center">
          <button class="landing-service__action timeout-btn d-inline-block">
            時數計算教學
          </button>
        </div>

        <!-- Product-Card Section -->
        <div class="landing-service__card-wrapper">
          <div
            class="landing-service__card service-card__banner card mx-3"
            style="width: 343px"
          >
            <img
              src="../assets/images/product-livingroom.png"
              class="card-img-top"
              width="343px"
              height="122"
              style="opacity: 1; transition: opacity 0.5s ease 0s"
              alt="..."
            />
            <div class="card-body">
              <div class="service-card__title">客廳清潔</div>
              <!-- Clean-Service -->
              <div class="card-listgroup d-flex flex-wrap mt-3">
                <div class="addition__list">
                  <span>
                    <fa :icon="['fas', 'circle']" />
                  </span>
                  沙發擦拭
                </div>
                <div class="addition__list">
                  <span>
                    <fa :icon="['fas', 'circle']" />
                  </span>
                  地板除塵
                </div>
                <div class="addition__list">
                  <span>
                    <fa :icon="['fas', 'circle']" />
                  </span>
                  桌、櫃擦拭
                </div>
                <div class="addition__list">
                  <span>
                    <fa :icon="['fas', 'circle']" />
                  </span>
                  地板清潔
                </div>
                <div class="addition__list">
                  <span>
                    <fa :icon="['fas', 'circle']" />
                  </span>
                  燈具表面擦拭
                </div>
                <div class="addition__list">
                  <span>
                    <fa :icon="['fas', 'circle']" />
                  </span>
                  雜物整理
                </div>
                <div class="addition__list">
                  <span>
                    <fa :icon="['fas', 'circle']" />
                  </span>
                  垃圾打包
                </div>
              </div>
              <!-- Dirty-Service -->
              <div class="card-listgroup d-flex flex-wrap mt-3">
                <div class="addition__list">
                  <span style="color: #c9302c">
                    <fa :icon="['fas', 'xmark']" />
                  </span>
                  沙發深層污漬
                </div>
                <div class="addition__list">
                  <span style="color: #c9302c">
                    <fa :icon="['fas', 'xmark']" />
                  </span>
                  地毯深層污漬
                </div>
                <div class="addition__list">
                  <span style="color: #c9302c">
                    <fa :icon="['fas', 'xmark']" />
                  </span>
                  天花板層板清潔
                </div>
                <div class="addition__list">
                  <span style="color: #c9302c">
                    <fa :icon="['fas', 'xmark']" />
                  </span>
                  吊燈清潔
                </div>
              </div>

              <div data-v-2c27a99f="" class="addition__list-description mt-1">
                建議您與潔客可採用安全之方式拆下後，交由潔客做清洗。
              </div>

              <div class="service-card__measures">
                <div class="measures__badge text-center">
                  <img
                    data-v-2c27a99f=""
                    width="28"
                    height="28"
                    src="../assets/images/clock.png"
                  />
                  <div class="measures__badge-text">0.5~1.5</div>
                </div>
                <div class="measures__comparison border">
                  <div class="measures__frames">
                    <span class="addition__list-description">普通清潔</span>
                    <span class="addition__list-description"
                      >空間大、許久未整理</span
                    >
                  </div>
                  <div class="measures__hr measures__frames"></div>
                  <div class="measures__hr-time measures__frames">
                    <span data-v-2c27a99f="">0.5 hr</span>
                    <span data-v-2c27a99f="">1.5 hr</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</template>

<script>
export default {
  name: "Platform",
};
</script>

<style scoped>
body {
  background-color: #f5f3f4;
}
.platform-landing__wrappper {
  display: flex;
  align-items: center;
  flex-direction: column;
  width: 100%;
}
.platform-landing__title {
  font-size: 32px;
  color: #3e4459;
  font-weight: 500;
  margin-bottom: 8px;
  padding-top: 40px;
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

.landing-service__card-wrapper {
  padding: 50px 0;
  display: flex;
  align-items: stretch;
  justify-content: center;
}

.service-card__title {
  font-size: 18px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.svg-inline--fa.fa-w-16 {
  width: 0.5rem;
}

.addition__list {
  width: 50%;
  font-size: 14px;
}

.addition__list-description {
  display: flex;
  justify-content: flex-start;
  font-size: 12px;
  color: #9b9b9b;
}

.service-card__measures {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-item-align: start;
  align-self: flex-start;
  margin-top: 20px;
  width: 100%;
}

.measures__comparison {
  flex: 1;
}

.measures__frames {
  display: flex;
  justify-content: space-between;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}
</style>
