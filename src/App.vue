<template>
  <div class="root">
    <div class="container-fluid navbarbg pr-0 pl-0">
      <div class="row row-cols-1 row-cols-lg-1">
        <div class="d-flex justify-content-center mr-0 navbar-brand">
          <img src="./assets/img/logo.png" alt="" />
        </div>
      </div>
      <nav class="navbar navbar-expand-lg d-flex justify-content-center">
        <div
          class="font-family-2 d-flex justify-content-center pl-0 pr-0 navbar navbar-expand-md"
        >
          <div class="row">
            <div class="col-12 col-lg-8 navbar__contents">
              <ul class="mr-auto nav">
                <li class="nav-item">
                  <a class="navlink p-lg-5 p-3" href="#premiere">Premiere</a>
                </li>
                <li class="nav-item">
                  <a class="navlink p-lg-5 p-3" href="#events">Events</a>
                </li>
                <li class="nav-item">
                  <a class="navlink p-lg-5 p-3" href="#images">Images</a>
                </li>
                <li class="nav-item">
                  <routerlink class="navlink p-lg-5 p-3" to="#"
                    >Review</routerlink
                  >
                </li>
              </ul>
            </div>
          </div>
        </div>
      </nav>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.navbar__contents {
  display: contents;
}
.navlink {
  text-decoration: none;
  cursor: pointer;
  color: #ecbb52;
}
.navlink:hover {
  color: #ecbb52;
}
.navbarbg {
  background-color: rgba(17, 16, 16, 0.8666666666666667);
  z-index: 1000;
  position: fixed;
}

.font-family-2 {
  font-family: GillSans;
}
</style>
