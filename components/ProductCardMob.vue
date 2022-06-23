<!-- Please remove this file from your project -->
<template>
  <body>
    <div
      class="
        landing-service__card-wrapper
        d-flex
        justify-content-center
        flex-wrap
      "
    >
      <!-- Card01 -->
      <div
        class="landing-service__card service-card__banner card mx-3 my-3"
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
        <div class="accordion accordion-flush" id="accordionFlushExample">
          <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingOne">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#flush-collapseOne"
                aria-expanded="false"
                aria-controls="flush-collapseOne"
              >
                <div class="service-card__title">客廳清潔</div>
              </button>
            </h2>
            <div
              id="flush-collapseOne"
              class="accordion-collapse collapse"
              aria-labelledby="flush-headingOne"
              data-bs-parent="#accordionFlushExample"
            >
              <div class="accordion-body">
                <div class="card-body">
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

                  <div class="addition__list-description mt-1">
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
                    <div class="measures__comparison mx-2">
                      <div class="measures__hr-label">
                        <span class="addition__list-description">普通清潔</span>
                        <span class="addition__list-description"
                          >空間大、許久未整理</span
                        >
                      </div>
                      <div class="measures__frames"></div>
                      <div class="measures__hr-time">
                        <span class="fw-bolder">0.5 hr</span>
                        <span class="fw-bolder">1.5 hr</span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Card02 -->
      <div
        class="landing-service__card service-card__banner card mx-3 my-3"
        style="width: 343px"
      >
        <img
          src="../assets/images/product-kitchen.png"
          class="card-img-top"
          width="343px"
          height="122"
          style="opacity: 1; transition: opacity 0.5s ease 0s"
          alt="..."
        />
        <div class="accordion accordion-flush" id="accordionFlushKitchen">
          <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingTwo">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#flush-collapseTwo"
                aria-expanded="false"
                aria-controls="flush-collapseTwo"
              >
                <div class="service-card__title">廚房清潔</div>
              </button>
            </h2>
            <div
              id="flush-collapseTwo"
              class="accordion-collapse collapse"
              aria-labelledby="flush-headingTwo"
              data-bs-parent="#accordionFlushKitchen"
            >
              <div class="accordion-body">
                <div class="card-body">
                  <!-- Clean-Service -->
                  <div class="card-listgroup d-flex flex-wrap mt-3">
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      流理檯擦拭
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      瓦斯爐台
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      集油槽油污處理
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      抽油煙機
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
                      冰箱外觀
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      洗碗、水槽清潔
                    </div>
                  </div>
                  <!-- Dirty-Service -->
                  <div class="card-listgroup d-flex flex-wrap mt-3">
                    <div class="addition__list">
                      <span style="color: #c9302c">
                        <fa :icon="['fas', 'xmark']" />
                      </span>
                      廚餘清理
                    </div>
                  </div>

                  <div class="service-card__measures">
                    <div class="measures__badge text-center">
                      <img
                        data-v-2c27a99f=""
                        width="28"
                        height="28"
                        src="../assets/images/clock.png"
                      />
                      <div class="measures__badge-text">1.0~2.5</div>
                    </div>
                    <div class="measures__comparison mx-2">
                      <div class="measures__hr-label">
                        <span class="addition__list-description">普通清潔</span>
                        <span class="addition__list-description"
                          >油污嚴重、許久未清潔理</span
                        >
                      </div>
                      <div class="measures__frames"></div>
                      <div class="measures__hr-time">
                        <span class="fw-bolder">1.0 hr</span>
                        <span class="fw-bolder">2.5 hr</span>
                      </div>
                      <div
                        class="
                          measures__additions-upper
                          d-flex
                          justify-content-between
                        "
                      >
                        <div class="measures__additions-title">
                          <span class="text-secondary">
                            <fa :icon="['fas', 'plus']" />
                          </span>
                          冰箱內部整理、清潔
                        </div>
                        <div class="measures__additions-des">
                          <span class="text-secondary">
                            <fa :icon="['fas', 'plus']" />
                          </span>
                          1 ~1.5 hr
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Card03 -->
      <div
        class="landing-service__card service-card__banner card mx-3 my-3"
        style="width: 343px"
      >
        <img
          src="../assets/images/product-balcony.png"
          class="card-img-top"
          width="343px"
          height="122"
          style="opacity: 1; transition: opacity 0.5s ease 0s"
          alt="..."
        />
        <div class="accordion accordion-flush" id="accordionFlushBalcony">
          <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingThree">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#flush-collapseThree"
                aria-expanded="false"
                aria-controls="flush-collapseThree"
              >
                <div class="service-card__title">陽台清潔</div>
              </button>
            </h2>
            <div
              id="flush-collapseThree"
              class="accordion-collapse collapse"
              aria-labelledby="flush-headingThree"
              data-bs-parent="#accordionFlushBalcony"
            >
              <div class="accordion-body">
                <div class="card-body">
                  <!-- Clean-Service -->
                  <div class="card-listgroup d-flex flex-wrap mt-3">
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      家電外觀擦拭
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      水管擦拭
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                        地板刷洗
                      </span>
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      曬衣桿擦拭
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      雜物整理
                    </div>
                  </div>
                  <!-- Dirty-Service -->
                  <div class="card-listgroup d-flex flex-wrap mt-3">
                    <div class="addition__list">
                      <span style="color: #c9302c">
                        <fa :icon="['fas', 'xmark']" />
                      </span>
                      除害蟲
                    </div>
                    <div class="addition__list">
                      <span style="color: #c9302c">
                        <fa :icon="['fas', 'xmark']" />
                      </span>
                      園藝、花草照料
                    </div>
                  </div>

                  <div class="service-card__measures">
                    <div class="measures__badge text-center">
                      <img
                        data-v-2c27a99f=""
                        width="28"
                        height="28"
                        src="../assets/images/clock.png"
                      />
                      <div class="measures__badge-text">1.0~1.5</div>
                    </div>
                    <div class="measures__comparison mx-2">
                      <div class="measures__hr-label">
                        <span class="addition__list-description">普通清潔</span>
                        <span class="addition__list-description">
                          空間大、許久未整理
                        </span>
                      </div>
                      <div class="measures__frames"></div>
                      <div class="measures__hr-time">
                        <span class="fw-bolder">1.0 hr</span>
                        <span class="fw-bolder">1.5 hr</span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Card04 -->
      <div
        class="landing-service__card service-card__banner card mx-3 my-3"
        style="width: 343px"
      >
        <img
          src="../assets/images/product-bathroom.png"
          class="card-img-top"
          width="343px"
          height="122"
          style="opacity: 1; transition: opacity 0.5s ease 0s"
          alt="..."
        />
        <div class="accordion accordion-flush" id="accordionFlushBathroom">
          <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingFour">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#flush-collapseFour"
                aria-expanded="false"
                aria-controls="flush-collapseFour"
              >
                <div class="service-card__title">浴室清潔</div>
              </button>
            </h2>
            <div
              id="flush-collapseFour"
              class="accordion-collapse collapse"
              aria-labelledby="flush-headingFour"
              data-bs-parent="#accordionFlushBathroom"
            >
              <div class="accordion-body">
                <div class="card-body">
                  <!-- Clean-Service -->
                  <div class="card-listgroup d-flex flex-wrap mt-3">
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      馬桶刷洗
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      鏡面光亮
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>

                      浴缸清潔
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>

                      磁磚刷洗
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      洗手檯面清潔
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      浴門清潔
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      垃圾打包
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      清理水垢、皂垢
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      局部小範圍除霉
                    </div>
                  </div>

                  <div class="service-card__measures">
                    <div class="measures__badge text-center">
                      <img
                        data-v-2c27a99f=""
                        width="28"
                        height="28"
                        src="../assets/images/clock.png"
                      />
                      <div class="measures__badge-text">1.0~1.5/間</div>
                    </div>
                    <div class="measures__comparison mx-2">
                      <div class="measures__hr-label">
                        <span class="addition__list-description">普通清潔</span>
                        <span class="addition__list-description"
                          >許久未清潔</span
                        >
                      </div>
                      <div class="measures__frames"></div>
                      <div class="measures__hr-time">
                        <span class="fw-bolder">1.0 hr</span>
                        <span class="fw-bolder">1.5 hr</span>
                      </div>
                      <div
                        class="
                          measures__additions-upper
                          d-flex
                          justify-content-between
                        "
                      >
                        <div class="measures__additions-title">
                          <span class="text-secondary">
                            <fa :icon="['fas', 'plus']" />
                          </span>
                          全區除霉
                        </div>
                        <div class="measures__additions-des">+ 4 hr</div>
                      </div>
                      <div class="addition__list-description mt-1">
                        因需用漂白水敷於發霉處3~4小時，因此全區除霉將耗時至少4~8小時(若霉菌已深入內部，有可能無法完全清除乾淨)
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Card05 -->
      <div
        class="landing-service__card service-card__banner card mx-3 my-3"
        style="width: 343px"
      >
        <img
          src="../assets/images/product-room.png"
          class="card-img-top"
          width="343px"
          height="122"
          style="opacity: 1; transition: opacity 0.5s ease 0s"
          alt="..."
        />
        <div class="accordion accordion-flush" id="accordionFlushRoom">
          <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingFive">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#flush-collapseFive"
                aria-expanded="false"
                aria-controls="flush-collapseFive"
              >
                <div class="service-card__title">臥室清潔</div>
              </button>
            </h2>
            <div
              id="flush-collapseFive"
              class="accordion-collapse collapse"
              aria-labelledby="flush-headingFive"
              data-bs-parent="#accordionFlushRoom"
            >
              <div class="accordion-body">
                <div class="card-body">
                  <!-- Clean-Service -->
                  <div class="card-listgroup d-flex flex-wrap mt-3">
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      衣櫃外觀擦拭
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      桌面清潔
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      棉被、衣物整理
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      家電外觀擦拭
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
                      雜物整理
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      床單換洗
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
                      家電拆卸清洗
                    </div>
                    <div class="addition__list">
                      <span style="color: #c9302c">
                        <fa :icon="['fas', 'xmark']" />
                      </span>
                      整理衣櫃內部衣物
                    </div>
                    <div class="addition__list">
                      <span style="color: #c9302c">
                        <fa :icon="['fas', 'xmark']" />
                      </span>
                      移動、搬移床鋪
                    </div>
                  </div>

                  <div class="service-card__measures">
                    <div class="measures__badge text-center">
                      <img
                        data-v-2c27a99f=""
                        width="28"
                        height="28"
                        src="../assets/images/clock.png"
                      />
                      <div class="measures__badge-text">0.5~1/間</div>
                    </div>
                    <div class="measures__comparison mx-2">
                      <div class="measures__hr-label">
                        <span class="addition__list-description">普通清潔</span>
                        <span class="addition__list-description"
                          >空間大、許久未清潔理</span
                        >
                      </div>
                      <div class="measures__frames"></div>
                      <div class="measures__hr-time">
                        <span class="fw-bolder">0.5 hr</span>
                        <span class="fw-bolder">1 hr</span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Card06 -->
      <div
        class="landing-service__card service-card__banner card mx-3 my-3"
        style="width: 343px"
      >
        <img
          src="../assets/images/product-loundry.png"
          class="card-img-top"
          width="343px"
          height="122"
          style="opacity: 1; transition: opacity 0.5s ease 0s"
          alt="..."
        />
        <div class="accordion accordion-flush" id="accordionFlushLoundry">
          <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingSix">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#flush-collapseSix"
                aria-expanded="false"
                aria-controls="flush-collapseSix"
              >
                <div class="service-card__title">其他清潔</div>
              </button>
            </h2>
            <div
              id="flush-collapseSix"
              class="accordion-collapse collapse"
              aria-labelledby="flush-headingSix"
              data-bs-parent="#accordionFlushLoundry"
            >
              <div class="accordion-body">
                <div class="card-body">
                  <div class="addition__list-description mt-1">
                    非主要清潔內容，但可增加時數請清潔人員執行
                  </div>
                  <div
                    class="
                      addition__title-wrapper
                      d-flex
                      justify-content-between
                      my-3
                    "
                  >
                    <div data-v-2c27a99f="" class="addition__title">
                      <span class="text-secondary">
                        <fa :icon="['fas', 'plus']" />
                      </span>
                      窗戶清潔
                    </div>
                    <div class="addition__des">+ 0.5hr/扇</div>
                  </div>
                  <!-- Clean-Service -->
                  <div class="card-listgroup d-flex flex-wrap">
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      內側、底溝擦拭
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      玻璃窗內部清洗
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      紗窗內部清潔
                    </div>
                  </div>
                  <!-- Dirty-Service -->
                  <div class="card-listgroup d-flex flex-wrap mt-3">
                    <div class="addition__list">
                      <span style="color: #c9302c">
                        <fa :icon="['fas', 'xmark']" />
                      </span>
                      拆卸窗戶清洗
                    </div>
                    <div class="addition__list">
                      <span style="color: #c9302c">
                        <fa :icon="['fas', 'xmark']" />
                      </span>
                      拆窗簾、清洗
                    </div>
                    <div class="addition__list-description mt-1">
                      以安全為前提下，『兩位』服務人員以上才提供拆洗窗戶、紗窗的服務，或者您可以自行拆下，再由服務人員做清洗
                    </div>
                  </div>

                  <div
                    class="
                      addition__title-wrapper
                      d-flex
                      justify-content-between
                      my-3
                    "
                  >
                    <div data-v-2c27a99f="" class="addition__title">
                      <span class="text-secondary">
                        <fa :icon="['fas', 'plus']" />
                      </span>
                      衣物洗曬
                    </div>
                    <div class="addition__des">+ 1~2 hr</div>
                  </div>

                  <!-- Clean-Service -->
                  <div class="card-listgroup d-flex flex-wrap">
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      衣物清洗
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      衣物晾曬
                    </div>
                    <div class="addition__list">
                      <span>
                        <fa :icon="['fas', 'circle']" />
                      </span>
                      需備有洗衣機
                    </div>
                  </div>
                  <!-- Dirty-Service -->
                  <div class="card-listgroup d-flex flex-wrap mt-3">
                    <div class="addition__list">
                      <span style="color: #c9302c">
                        <fa :icon="['fas', 'xmark']" />
                      </span>
                      特殊清洗衣物(乾洗)
                    </div>
                    <div class="addition__list">
                      <span style="color: #c9302c">
                        <fa :icon="['fas', 'xmark']" />
                      </span>
                      手洗衣物
                    </div>
                    <div class="addition__list">
                      <span style="color: #c9302c">
                        <fa :icon="['fas', 'xmark']" />
                      </span>
                      整燙衣物
                    </div>
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
  name: "ProductCard",
  components: {},
};
</script>

<style scoped>
.landing-service__card-wrapper {
  padding: 50px 0;
  align-items: stretch;
  max-width: 1400px;
  margin: 0 auto;
}

.landing-service__card {
  box-shadow: 1px 2px 7px 7px rgb(229 229 229 / 50%);
}

.service-card__title {
  font-size: 18px;
  display: flex;
  align-items: center;
  justify-content: space-between;
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
  display: flex;
  align-self: flex-start;
  margin-top: 20px;
  width: 100%;
}

.measures__comparison {
  flex: 1;
}

.measures__hr-label,
.measures__additions-upper,
.measures__hr-time {
  display: flex;
  justify-content: space-between;
  font-size: 12px;
}
.measures__frames {
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: relative;
  border-bottom: 3px solid #eee;
  margin: 12px 0;
  position: relative;
}

.measures__frames::before {
  position: absolute;
  content: "";
  width: 3px;
  height: 20px;
  transform: translateY(1px);
  left: 0;
  background-color: #eee;
  box-sizing: border-box;
}

.measures__frames::after {
  position: absolute;
  content: "";
  width: 3px;
  height: 20px;
  transform: translateY(1px);
  right: 0;
  background-color: #eee;
}

.accordion-button {
  color: black;
  background-color: white;
  box-shadow: none;
}

.accordion-body {
  padding: 0;
}
</style>
