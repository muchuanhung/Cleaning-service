<template>
  <div class="header container">
    <!-- Web -->
    <header class="d-none d-md-block">
      <div class="d-flex flex-wrap justify-content-center">
        <a
          href="/"
          class="d-flex align-items-center mb-3 mb-md-0 me-md-auto nav-logo"
        >
          <img
            src="https://i.imgur.com/sTG67Vj.png"
            alt="logo"
            class="nav-logo img"
          />
        </a>

        <ul class="nav nav-pills d-flex align-items-center">
          <li class="nav-item">
            <a href="#" class="nav-home" aria-current="page">
              <span>
                <fa :icon="['fas', 'house-chimney']" />
              </span>
              找打掃
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link">
              <span>
                <fa :icon="['fas', 'briefcase']" />
              </span>
              辦公室清潔
            </a>
          </li>
          <div class="dropdown">
            <button
              class="nav-link dropdown-toggle"
              type="button"
              id="dropdownMenuButton1"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              全部服務
            </button>
            <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
              <li><a class="dropdown-item" href="#">清潔整理</a></li>
              <li><a class="dropdown-item" href="#">家電清洗</a></li>
              <li><a class="dropdown-item" href="#">其他服務</a></li>
            </ul>
          </div>
          <li class="nav-item"><a href="#" class="nav-member">成為潔客</a></li>
          <li class="nav-item"><a href="#" class="nav-link">生活知識站</a></li>
          <li class="nav-item">
            <a href="#" class="nav-register">註冊登入</a>
          </li>
        </ul>
      </div>
    </header>
    <!-- Mobile -->
    <header class="d-block d-md-none">
      <div class="d-flex flex-wrap justify-content-between align-items-center">
        <a href="/" class="d-flex align-items-center nav-logo">
          <img
            src="https://i.imgur.com/sTG67Vj.png"
            alt="logo"
            class="nav-logo img"
          />
        </a>
        <button
          type="button"
          class="border-0"
          style="background: transparent"
          data-bs-toggle="offcanvas"
          data-bs-target="#offcanvasRight"
          aria-controls="offcanvasRight"
        >
          <img
            src="https://i.imgur.com/aHn0wGV.png"
            width="28"
            height="28"
            alt="漢堡排"
          />
        </button>

        <div
          class="offcanvas offcanvas-end w-50"
          tabindex="-1"
          id="offcanvasRight"
          aria-labelledby="offcanvasRightLabel"
        >
          <div class="offcanvas-body mt-3">
            <ul class="nav nav-pills d-flex align-items-center">
              <li class="nav-item">
                <a href="#" class="nav-home" aria-current="page">
                  <span>
                    <fa :icon="['fas', 'house-chimney']" />
                  </span>
                  找打掃
                </a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link">
                  <span>
                    <fa :icon="['fas', 'briefcase']" />
                  </span>
                  辦公室清潔
                </a>
              </li>
              <div class="dropdown">
                <button
                  class="nav-link dropdown-toggle"
                  type="button"
                  id="dropdownMenuButton1"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  全部服務
                </button>
                <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                  <li><a class="dropdown-item" href="#">清潔整理</a></li>
                  <li><a class="dropdown-item" href="#">家電清洗</a></li>
                  <li><a class="dropdown-item" href="#">其他服務</a></li>
                </ul>
              </div>
              <li class="nav-item">
                <a href="#" class="nav-member">成為潔客</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link">生活知識站</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-register">註冊登入</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>
<script>
export default {
  name: "Header",
};
</script>

<style scoped>
a {
  text-decoration: none;
}

.nav-logo img {
  max-width: 260px;
  max-height: 45px;
  height: 100%;
  width: auto;
}
.nav-pills {
  font-size: 14px;
}

.nav-home,
.nav-member,
.nav-link,
.nav-register {
  border-radius: 50px;
  margin: 12px 0;
  padding: 5px 12px;
  letter-spacing: 1px;
}
.nav-home {
  background-color: #36bbd9;
  color: white;
}

.nav-member {
  color: #36bbd9;
}

.nav-link {
  color: gray;
}

.nav-register {
  background-color: #fff;
  color: #36bbd9;
  border: 1px solid #36bbd9;
}

.nav-link:hover,
.nav-member:hover {
  background-color: rgba(238, 238, 238, 0.5);
  border-radius: 50px;
}

.nav-home:hover {
  background-color: rgba(238, 238, 238, 0.5);
  border-radius: 50px;
  color: white;
}

.nav-register:hover {
  background-color: #eee;
  color: #9b9b9b;
  border-color: transparent;
  border-radius: 50px;
}
</style>
