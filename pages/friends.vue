<template>
  <div>
    <div class="container mob_nav">
      <i class="fas fa-arrow-left fs-1" style="color: #f05342"></i>
      <img width="100px" src="~/assets/images/logo.png" alt="" />
      <i class="ms-2 fas fa-comments-alt fs-1" style="color: #f05342"></i>
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
          >
            Add New Friend <i class="fas fa-plus"></i>
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
          <p class="mb-1 fs-5">Friends</p>
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
            <div class="tabs active">
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
            <div
              class="create_content2 for_display"
              style="
                display: flex;
                justify-content: center;
                align-items: center;
              "
            >
              <div
                class="mt-3 mt-lg-0 d-flex justify-content-center align-items-center"
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
            </div>

            <div class="mb-4 mt-4 mt-lg-0">
              <p class="mb-0 ms-3">4 Friends</p>
              <div class="invitation_tabs mt-0 mt-lg-3">
                <div class="invitaion_tab">
                  <div class="d-flex justify-content-start align-items-start">
                    <img
                      class="mt-1"
                      src="~/assets/images/character1.png"
                      alt=""
                    />
                    <div
                      class="d-flex justify-content-start align-items-center flex-column"
                    >
                      <p class="mb-0 ms-2">Wyatt Hernandez</p>
                      <p class="mb-0 ms-3 text-muted">Last online 2h ago</p>
                    </div>
                  </div>
                </div>

                <div class="invitaion_tab">
                  <div class="d-flex justify-content-start align-items-start">
                    <img
                      class="mt-1"
                      src="~/assets/images/character2.png"
                      alt=""
                    />
                    <div
                      class="d-flex justify-content-start align-items-center flex-column"
                    >
                      <p class="mb-0" style="margin-left: -12px">
                        Jacob Mitchell
                      </p>
                      <p class="mb-0 ms-3 text-muted">Last online 2h ago</p>
                    </div>
                  </div>
                </div>

                <div class="invitaion_tab">
                  <div class="d-flex justify-content-start align-items-start">
                    <img
                      class="mt-1"
                      src="~/assets/images/character4.png"
                      alt=""
                    />
                    <div
                      class="d-flex justify-content-start align-items-center flex-column"
                    >
                      <p class="mb-0">Samuel Sanchez</p>
                      <p class="mb-0 ms-3 text-muted">Last online 2h ago</p>
                    </div>
                  </div>
                </div>

                <div class="invitaion_tab">
                  <div class="d-flex justify-content-start align-items-start">
                    <img
                      class="mt-1"
                      src="~/assets/images/character3.png"
                      alt=""
                    />
                    <div
                      class="d-flex justify-content-start align-items-center flex-column"
                    >
                      <p class="mb-0">Samuel Sanchez</p>
                      <p class="mb-0 ms-3 text-muted">Last online 2h ago</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="for_display mb-2">
              <b-form-input
                class="text-white m-2"
                v-model="text"
                placeholder="Enter Username"
                style="width: 300px"
              ></b-form-input>
              <button class="login2 setup m-2" style="background-color: #06A361; border: none">
                Add a new Friend <i class="fas fa-arrow-right text-white"></i>
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
