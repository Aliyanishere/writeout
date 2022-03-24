<template>
  <div>
    <div class="container mob_nav">
      <i class="fas fa-arrow-left fs-4" style="color: #f05342"></i>
      <img width="100px" src="~/assets/images/logo.png" alt="" />
      <i class="fas fa-ellipsis-v fs-2" style="color: #f05342"></i>
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
          <button
            class="add_new mb-2 mb-md-2 mt-3 mt-md-3 mt-lg-0 mb-lg-4 me-0 me-md-0 me-lg-5"
            style="display: flex; justify-content: center; width: 150px"
          >
            Watch Game
          </button>
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

          <div
            class="create_content2"
            style="display: flex; justify-content: center; align-items: center"
          >
            <div
              class="mt-5 mt-lg-0 d-flex justify-content-center align-items-center"
            >
              <img width="160px" src="~/assets/images/profile.png" alt="" />
            </div>

            <div
              class="mt-3 d-flex justify-content-center align-items-center flex-column"
            >
              <p class="mb-0">
                @Koala23 <img src="~assets/images/verify.png" alt="" />
              </p>
              <p class="mb-0">Playing since 2020</p>
            </div>

            <div
              class="mt-5 mt-lg-3 d-flex justify-content-between align-items-center"
              style="width: 260px"
            >
              <div
                class="d-flex justify-content-between align-items-center flex-column"
              >
                <p class="mb-0 fw-bold fs-3">1000</p>
                <p class="fw-200">LOSSES</p>
              </div>
              <div
                class="d-flex justify-content-between align-items-center flex-column"
              >
                <p class="mb-0 fw-bold fs-3">500</p>
                <p class="fw-200">WINS</p>
              </div>
              <div
                class="d-flex justify-content-between align-items-center flex-column"
              >
                <p class="mb-0 fw-bold fs-3">1000</p>
                <p class="fw-200">LOSSES</p>
              </div>
            </div>

            <div class="setup mt-3 mt-lg-0">
              <button
                class="login2 mb-0 mt-0"
                style="display: flex; justify-content: center; width: 260px"
              >
                <i class="fas fa-heart text-white me-2"></i> Send Extra Life
              </button>
              <button
                class="login2 mt-2 mb-2"
                style="display: flex; justify-content: center; width: 260px"
              >
                <img
                  class="me-2"
                  src="~assets/images/second_chance.png"
                  alt=""
                />
                Send Second Chance
              </button>
            </div>

            <div
              class="grant_verify mt-3 d-flex justify-content-center align-items-center flex-column"
            >
              <img src="~assets/images/reward.png" alt="" />
              <p class="mb-0">Grant Verified</p>
              <img src="~assets/images/progress.png" alt="" />
            </div>

            <div>
              <button class="add_new2 mb-4 mt-5 mb-lg-4">Watch Game</button>
            </div>
          </div>

          <div class="block_btn">
            <button v-b-modal.modal-sm.modal-center>Block</button>
            <b-modal
              id="modal-center"
              size="sm"
              title=""
              centered
              ok-title="Block"
              cancel-variant="dark"
            >
              <h6 class="text-white w-100 text-center">Confirm Blocking ?</h6>
            </b-modal>
          </div>
          <div class="banuser_btn">
            <button v-b-modal.modal-sm.modal-center>Ban User</button>
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
