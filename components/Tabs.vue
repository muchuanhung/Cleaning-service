<!-- Please remove this file from your project -->
<template>
  <div id="tabs" class="container">
    <div class="tabs">
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
          <div class="cascader">
            <button
              class="btn btn-default dropdown-toggle"
              type="button"
              id="dropdownMenuButton1"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              台北市 中正區
            </button>
            <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
              <li><a class="dropdown-item" href="#">Action</a></li>
              <li><a class="dropdown-item" href="#">Another action</a></li>
              <li><a class="dropdown-item" href="#">Something else here</a></li>
            </ul>
          </div>
        </table>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Tabs",
  data: function () {
    return {
      activetab: "1",
    };
  },
};
</script>

<style scoped>
/* RESET */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 620px;
  min-width: 420px;
  margin: 40px auto;
  font-family: "Nunito Sans", Arial, Helvetica, sans-serif;
  font-size: 0.9em;
  color: #888;
}

/* Style the tabs */
.tabs {
  overflow: hidden;
  margin-bottom: -2px; /* hide bottom border */
  margin-left: 24px;
  display: flex;
}

.tabs a {
  float: left;
  cursor: pointer;
  transition: background-color 0.2s;
  border-right: none;
  text-decoration: none;
  font-weight: 400;
  font-size: 16px;
  padding: 6px 12px;
  border-radius: 4px 4px 0 0;
  color: #9b9b9b;
  background-color: #eee;
  flex: 1;
  margin-right: 2px;
}

/* Change background color of tabs on hover */
.tabs a:hover {
  background-color: #aaa;
  color: #fff;
}

/* Styling for active tab */
.tabs a.active {
  background-color: rgba(255, 255, 255, 0.3);
  color: #36bbd9;
  border-bottom: 2px solid #fff;
  cursor: default;
}

/* Style the tab content */
.tabcontent {
  background-color: rgba(255, 255, 255, 0.8);
  padding: 20px 30px;
}

.cascader {
  display: flex;
  padding: 8px 40px 8px 16px;
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
}
</style>
