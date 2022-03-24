<template>
  <div>
    <div class="mob_nav2">
      <img width="100px" src="~/assets/images/logo.png" alt="" />
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
        <div class="mb-2 mb-lg-5 create_game mt-2 mt-lg-5 mt-lg-0">
          <i class="fas fa-arrow-left fs-4 me-3" style="color: #f05342"></i>
          <p class="mb-1 fs-5">Create New Game</p>
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
            <div class="tabs">
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
            <b-form-input
              class="w-100 w-lg-50 text-white"
              v-model="text"
              placeholder="Enter a Creative Title"
            ></b-form-input>

            <div class="mt-4">
              <p class="mb-0 ms-3 ms-lg-0">Characters</p>
              <div class="charac_tabs">
                <div class="charac_tab">
                  <img src="~/assets/images/character1.png" alt="" />
                  <p class="mb-0 ms-2">Taylor</p>
                  <i class="fas fa-times text-white ms-3 ms-lg-4"></i>
                </div>
                <div class="charac_tab">
                  <img src="~/assets/images/character2.png" alt="" />
                  <p class="mb-0 ms-2 me-2 me-lg-0">Jay</p>
                  <i class="fas fa-times text-white ms-4 ms-lg-5"></i>
                </div>
                <div class="charac_tab">
                  <img src="~/assets/images/character3.png" alt="" />
                  <p class="mb-0 ms-2 me-1 me-lg-3">Tyler</p>
                  <i class="fas fa-times text-white ms-4 ms-lg-4"></i>
                </div>
                <div class="charac_tab">
                  <img src="~/assets/images/character4.png" alt="" />
                  <p class="mb-0 ms-2">Devon</p>
                  <i class="fas fa-times text-white ms-3 ms-lg-4"></i>
                </div>
                <div class="add_tab" v-b-modal.modal-sm.modal-center>
                  <p class="mb-0 fs-6 fw-bold">Add</p>
                  <i class="fas fa-plus text-white ms-2"></i>
                </div>

                <b-modal
                  id="modal-center"
                  size="sm"
                  title="Add Character"
                  centered
                  ok-title="Add"
                  cancel-variant="dark"
                >
                  <input
                    class="ps-3 ms-3"
                    style="width: 90%"
                    type="text"
                    placeholder="Enter Character Name"
                  />
                </b-modal>
              </div>
            </div>

            <div class="mt-4 ms-2 ms-lg-0">
              <p>Number of Players</p>
              <div class="players_num">
                <p class="players_numbers tab_num_1" v-on:click="tab('tab_num_1')">1</p>
                <p class="players_numbers tab_num_2" v-on:click="tab('tab_num_2')">2</p>
                <p class="players_numbers tab_num_3" v-on:click="tab('tab_num_3')">3</p>
                <p class="players_numbers btn_active tab_num_4" v-on:click="tab('tab_num_4')">4</p>
                <p class="players_numbers tab_num_5" v-on:click="tab('tab_num_5')">5</p>
                <p class="players_numbers tab_num_6" v-on:click="tab('tab_num_6')">6</p>
                <p class="players_numbers tab_num_7" v-on:click="tab('tab_num_7')">7</p>
                <p class="players_numbers tab_num_8" v-on:click="tab('tab_num_8')">8</p>
              </div>
            </div>

            <div class="mt-3 mt-lg-4 mb-0">
              <p class="mb-0 ms-2 ms-lg-0">Start Time</p>
              <div class="start_time">
                <div class="date mb-0" v-b-modal.modal-sm.modal-center-2>
                  <i class="fas fa-calendar-alt"></i>
                  <p class="mb-0 ms-2">Jan 12,2022</p>
                </div>
                <div class="date mb-0" v-b-modal.modal-sm.modal-center-2>
                  <i class="fas fa-clock"></i>
                  <p class="mb-0 ms-2">05:00 PM</p>
                </div>
              </div>
              <b-modal class="w-100 text-center" id="modal-center-2" centered size="sm">
                <b-row>
                  <p class="d-flex justify-content-center align-items-center">
                    Choose Date
                  </p>
                  <b-col md="auto">
                    <b-calendar
                      v-model="value"
                      @context="onContext"
                      locale="en-US"
                      class="text-white mx-0 px-0"
                    ></b-calendar>
                  </b-col>
                </b-row>

                <b-row>
                  <b-col md="auto">
                    <b-time
                      v-model="value"
                      locale="en"
                      @context="onContext"
                    ></b-time>
                  </b-col>
                </b-row>
              </b-modal>
            </div>

            <div class="setup mt-0">
              <button class="login2">
                Setup Game <i class="fas fa-arrow-right text-white"></i>
              </button>
            </div>
          </div>
        </div>
      </div>

      <img class="poly1" src="~/assets/images/polygon1.svg" alt="">
      <img class="poly2" src="~/assets/images/polygon2.svg" alt="">
      <img class="poly3" src="~/assets/images/polygon3.svg" alt="">
      <img class="poly4" src="~/assets/images/polygon4.svg" alt="">

      <img class="mob_poly1" src="~/assets/images/mob_Polygon1.svg" alt="" />
      <img class="mob_poly2" src="~/assets/images/mob_polygon2.svg" alt="" />
      <img class="mob_poly3" src="~/assets/images/mob_polygon3.svg" alt="" />
      <img class="mob_poly4" src="~/assets/images/mob_polygon4.svg" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      value: "",
      context: null,
    };
  },
  methods: {
    onContext(ctx) {
      this.context = ctx;
    },
  },
};
</script>

<script>
export default {
  data() {
    return {
      value: "",
      context: null,
    };
  },
  methods: {
    onContext(ctx) {
      this.context = ctx;
    },
  },
};
</script>



<script>
export default {
  methods: {
    tab(ele) {
      
      document.querySelectorAll('.players_numbers').forEach(element => {
        element.classList.remove("btn_active")
      });
     document.querySelector("."+ele).classList.add("btn_active")
    // ele.classList.add("btn_active")
    // console.log(ele)
    },
  },
};
</script>
