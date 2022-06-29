<!-- Please remove this file from your project -->
<template>
  <div id="reserve-form" class="container">
    <div class="reserve-formwrapper">
      <a
        v-on:click="activetab = '1'"
        v-bind:class="[activetab === '1' ? 'active' : '']"
      >
        快速預約
      </a>
      <a
        v-on:click="activetab = '2'"
        v-bind:class="[activetab === '2' ? 'active' : '']"
      >
        雙人快清
      </a>
      <a
        v-on:click="activetab = '3'"
        v-bind:class="[activetab === '3' ? 'active' : '']"
      >
        指定人員
      </a>
      <a
        v-on:click="activetab = '4'"
        v-bind:class="[activetab === '4' ? 'active' : '']"
      >
        定期享優惠
      </a>
    </div>

    <div class="content">
      <div v-if="activetab === '1'" class="tabcontent">
        <table>
          <div class="w-100">
            <div class="cascader">
              <button
                class="
                  btn btn-default
                  dropdown-toggle
                  d-flex
                  justify-content-between
                  w-100
                "
                type="button"
                id="dropdownMenuButton1"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                <div class="text-muted">
                  <span class="icon-dot me-2">
                    <fa :icon="['fas', 'location-dot']" />
                  </span>

                  台北市 中正區
                </div>

                <span class="icon-dot">
                  <fa :icon="['fas', 'sort-down']" />
                </span>
              </button>
              <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                <li><a class="dropdown-item" href="#">Testing1</a></li>
                <li><a class="dropdown-item" href="#">Testing2</a></li>
              </ul>
            </div>
            <div class="cascader mt-3">
              <button
                class="
                  btn btn-default
                  dropdown-toggle
                  d-flex
                  justify-content-between
                  w-100
                "
                type="button"
                id="dropdownMenuButton1"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                <div class="text-muted">
                  <span class="icon-dot me-2">
                    <fa :icon="['fas', 'clock']" />
                  </span>
                  單人打掃3小時
                </div>

                <span class="icon-dot">
                  <fa :icon="['fas', 'sort-down']" />
                </span>
              </button>
              <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                <li><a class="dropdown-item" href="#">Testing1</a></li>
                <li><a class="dropdown-item" href="#">Testing2</a></li>
              </ul>
            </div>

            <div
              class="
                mt-3
                d-flex
                justify-content-between
                align-items-center
                px-3
              "
            >
              <label class="d-flex">
                <span class="icon-dot me-2">
                  <fa :icon="['fas', 'paw']" />
                </span>
                <p class="color-secondary">家中有無寵物？</p>
              </label>

              <div class="form-check form-switch">
                <input
                  class="form-check-input"
                  type="checkbox"
                  role="switch"
                  id="flexSwitchCheckDefault"
                />
              </div>
            </div>

            <div class="w100 text-center mt-3">
              <button class="reserve-btn w-100">開始預約，查看清潔價格</button>
            </div>

            <div class="w100 text-center mt-3">
              <p>
                找約過的人員？
                <a href="#" class="color-primary text-decoration-none">
                  輸入您的手機號碼
                </a>
              </p>
            </div>
          </div>
        </table>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ReserveForm",
  data: function () {
    return {
      activetab: "1",
    };
  },
};
</script>

<style scoped>
.color-primary {
  color: #36bbd9;
}

.container {
  width: 100%;
  margin: 40px auto;
  background-color: transparent;
  font-family: "Nunito Sans", Arial, Helvetica, sans-serif;
  font-size: 0.9em;
  color: #888;
}

/* Style the tabs */
.reserve-formwrapper {
  overflow: hidden;
  margin-bottom: -2px; /* hide bottom border */
  margin-left: 24px;
  display: flex;
}

.reserve-formwrapper a {
  float: left;
  cursor: pointer;
  transition: background-color 0.2s;
  border-right: none;
  text-decoration: none;
  font-weight: 400;
  font-size: 12px;
  padding: 6px;
  border-radius: 4px 4px 0 0;
  color: #9b9b9b;
  background-color: #eee;
  flex: 1;
  margin-right: 2px;
}

/* Change background color of tabs on hover */
.reserve-formwrapper a:hover {
  background-color: #aaa;
  color: #fff;
}

/* Styling for active tab */
.reserve-formwrapper a.active {
  background-color: rgba(255, 255, 255, 0.3);
  color: #36bbd9;
  cursor: default;
}

/* Style the tab content */
.tabcontent {
  background-color: rgba(255, 255, 255, 0.8);
  padding: 20px 30px;
  display: grid;
}

.cascader {
  display: flex;
  padding: 8px 16px;
  position: relative;
  border: 1px solid #eeeeee;
  border-radius: 4px;
  font-size: 14px;
  font-weight: normal;
  cursor: pointer;
  align-items: center;
  background-color: #ffffff;
  color: #3e4459;
  transition: 0.2s;
  min-width: 200px;
  width: 100%;
  justify-content: space-between;
}

.cascader:active {
  border: 1px solid #3e4459;
}

.dropdown-toggle::after {
  display: none;
}

.icon-dot {
  opacity: 0.5;
}

.icon-dot:active {
  opacity: 1;
}

.reserve-btn {
  display: inline-block;
  padding: 6px 12px;
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

.form-check-input {
  position: relative;
  display: inline-block;
  width: 58px;
  height: 32px;
  background-color: #fff;
  transition: 0.3s;
  border-radius: 16px;
  border: 1px solid #eee;
  margin: 3px 0;
  cursor: pointer;
}

@media (min-width: 768px) {
  .tabs a {
    font-size: 16px;
  }
}
</style>
