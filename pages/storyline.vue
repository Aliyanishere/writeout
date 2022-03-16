<template>
  <div>
    <div class="container mob_nav">
      <i class="fas fa-arrow-left fs-4" style="color: #f05342"></i>
      <img
        width="100px"
        src="~/assets/images/logo.png"
        alt=""
        style="margin-left: -20px"
      />
      <i class="fas fa-comments-alt fs-1" style="color: #f05342"></i>
    </div>

    <b-navbar
      class="container navbar"
      toggleable="lg"
      type="transparent"
      variant="transparent"
    >
      <b-navbar-brand href="#">
        <img width="100px" src="~/assets/images/logo.png" alt="" />
      </b-navbar-brand>

      <b-navbar-toggle class="text-white" target="nav-collapse"
        ><i class="fas fa-bars fs-4 text-white"></i
      ></b-navbar-toggle>

      <b-collapse id="nav-collapse" class="mx-auto" is-nav>
        <b-navbar-nav
          class="ms-auto mb-2 mb-lg-0 d-flex justify-content-center align-items-center"
        >
          <p
            class="text-white mb-2 mb-md-2 mt-3 mt-md-3 mt-lg-0 mb-lg-4 me-0 me-md-0 me-lg-3"
          >
            @Koala23
          </p>
          <div
            class="d-flex flex-column justify-content-center align-items-center"
          >
            <img src="~/assets/images/user_icon.svg" alt="" />
            <div class="d-flex justify-content-center align-items-center">
              <img
                class="mt-2 me-1"
                src="~/assets/images/coin.svg"
                alt=""
              />
              <p class="mb-0 mt-2" style="color: #E7A52E">2500</p>
            </div>
          </div>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>

    <div class="bg2">
      <div class="container" style="margin-top: 150px">
        <div class="mb-2 mb-lg-5 create_game2 mt-2 mt-lg-5 mt-lg-0">
          <i class="fas fa-arrow-left fs-4 me-3" style="color: #f05342"></i>
          <p class="mb-1 fs-5">Game</p>
        </div>

        <div class="main_create">
          <div class="sidebar mb-5">
            <NuxtLink to="/home">
            <div class="tabs">
              <i class="fas fa-home text-white fs-5 me-3"></i>
              <p class="mb-0 fs-6">Home</p>
            </div>
            </NuxtLink>
            <NuxtLink to="/friends">
            <div class="tabs">
              <i class="fas fa-user-friends text-white fs-5 me-3"></i>
              <p class="mb-0 fs-6">Friends</p>
            </div>
            </NuxtLink>
            <NuxtLink to="/game">
            <div class="tabs">
              <i class="fas fa-gamepad text-white fs-5 me-3"></i>
              <p class="mb-0 fs-6">Your Games</p>
            </div>
            </NuxtLink>
            <NuxtLink to="/writeout_shop">
            <div class="tabs">
              <i class="fas fa-store text-white fs-5 me-3"></i>
              <p class="mb-0 fs-6">Writeout Shop</p>
            </div>
            </NuxtLink>
            <NuxtLink to="/storyline">
            <div class="tabs active">
              <i class="fab fa-discord text-white fs-5 me-3"></i>
              <p class="mb-0 fs-6">Join the Discord</p>
            </div>
            </NuxtLink>
            <NuxtLink to="/terms">
            <div class="tabs">
              <i class="fas fa-info-circle text-white fs-5 me-3"></i>
              <p class="mb-0 fs-6">Terms of Service</p>
            </div>
            </NuxtLink>
            <NuxtLink to="/privacypolicy">
            <div class="tabs">
              <i class="fas fa-info-circle text-white fs-5 me-3"></i>
              <p class="mb-0 fs-6">Privacy Policy</p>
            </div>
            </NuxtLink>
            <NuxtLink to="/profile">
            <div class="tabs">
              <i class="fas fa-cog text-white fs-5 me-3"></i>
              <p class="mb-0 fs-6">Settings</p>
            </div>
            </NuxtLink>
            <NuxtLink to="/">
            <div class="tabs">
              <i class="fas fa-sign-out-alt text-white fs-5 me-3"></i>
              <p class="mb-0 fs-6">Logout</p>
            </div>
            </NuxtLink>
          </div>

          <div class="create_content">
            <div class="game_will_start_in mt-0">
              <p class="fs-4 ms-0 ms-lg-5">The Dunkin Disaster</p>
              <div
                class="ms-0 ms-lg-5 d-flex justify-content-center align-items-center"
              >
                <i class="mx-1 fas fa-heart" style="color: #ea2263"></i>
                <i class="mx-1 fas fa-heart" style="color: #ea2263"></i>
                <i class="mx-1 far fa-heart" style="color: #ea2263"></i>
              </div>
            </div>

            <div class="mt-4">
              <p class="mb-0 ms-3 ms-lg-0">Characters</p>
              <div class="charac_tabs">
                <div class="charac_tab2 btn_active tab_num_1" v-on:click="tab('tab_num_1')">
                  <!-- <img src="~/assets/images/character1.png" alt="" /> -->
                  <p class="mb-0 ms-4">Taylor</p>
                </div>
                <div class="charac_tab2 ps-4  tab_num_2"  v-on:click="tab('tab_num_2')">
                  <!-- <img src="~/assets/images/character2.png" alt="" /> -->
                  <p class="mb-0 ms-4">Jay</p>
                </div>
                <div class="charac_tab2 ps-3 tab_num_3"  v-on:click="tab('tab_num_3')">
                  <!-- <img src="~/assets/images/character3.png" alt="" /> -->
                  <p class="mb-0 ms-4">Tyler</p>
                </div>
                <div class="charac_tab2 tab_num_4" v-on:click="tab('tab_num_4')">
                  <!-- <img src="~/assets/images/character4.png" alt="" /> -->
                  <p class="mb-0 ms-4">Devon</p>
                </div>
              </div>
            </div>

            <div class="ps-3 ps-lg-0 text-start w-100">
              <p class="mb-2 mt-4 text-start">Enter line</p>
            </div>
            <div class="px-3 px-lg-0 w-100">
              <b-form-textarea
                id="textarea-rows"
                placeholder="Write here"
                rows="6"
                class="text-white"
              ></b-form-textarea>
            </div>

            <div class="setup">
              <button
                class="login2 mb-2"
                style="display: flex; justify-content: center"
              >
                Submit Story Line
              </button>
            </div>
          </div>
        </div>
      </div>

      <img class="poly1" src="~/assets/images/polygon1.svg" alt="">
      <img class="poly2" src="~/assets/images/polygon2.svg" alt="">
      <img class="poly3" src="~/assets/images/polygon3.svg" alt="">
      <img class="poly4" src="~/assets/images/polygon4.svg" alt="">
    </div>
  </div>
</template>




<script>
export default {
  methods: {
    tab(ele) {
      
      document.querySelectorAll('.charac_tab2').forEach(element => {
        element.classList.remove("btn_active")
      });
     document.querySelector("."+ele).classList.add("btn_active")
    // ele.classList.add("btn_active")
    // console.log(ele)
    },
  },
};
</script>
