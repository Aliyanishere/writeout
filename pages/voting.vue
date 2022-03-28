<template>
  <div>
    <div class="container mob_nav">
      <i class="fas fa-arrow-left fs-4 me-4" style="color: #f05342"></i>
      <img width="100px" src="~/assets/images/logo.png" alt="" />
      <div>
        <i class="fas fa-heart" style="color: #ea2263"></i>
        <i class="fas fa-heart" style="color: #ea2263"></i>
        <i class="far fa-heart" style="color: #ea2263"></i>
      </div>
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
          class="
            ms-auto
            mb-2 mb-lg-0
            d-flex
            justify-content-center
            align-items-center
          "
        >
          <p
            class="
              text-white
              mb-2 mb-md-2
              mt-3 mt-md-3 mt-lg-0
              mb-lg-4
              me-0 me-md-0 me-lg-3
            "
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

          <div class="create_content2"
          style="display: flex; justify-content: center; align-items: center">
            <div class="switches">
              <NuxtLink to="/your_line">
                <button class="chat_switch2">
                  Game
                </button>
              </NuxtLink>
              <NuxtLink to="/chat">
              <button class="writers_switch2">Chat</button>
              </NuxtLink>
            </div>

            <div class="d-flex align-items-center">
              <div class="game_will_start_in">
                <div class="round1">
                  <p class="text-danger mb-0">Round 3 Voting</p>
                </div>
                <p class="fs-4">00:09s</p>
              </div>

              <div class="ms-4 for_hide">
                <i class="far fa-heart fs-5" style="color: #ea2263"></i>
                <i class="far fa-heart fs-5" style="color: #ea2263"></i>
                <i class="far fa-heart fs-5" style="color: #ea2263"></i>
              </div>
            </div>

            <div class="mt-4">
              <div class="invitation_tabs mb-5 mb-lg-0 justify-content-center align-items-center flex-column">
                <div class="lines_tab">
                  <div class="d-flex justify-content-start align-items-start">
                    <div
                      class="
                        d-flex
                        justify-content-start
                        align-items-start
                        flex-column
                      "
                      style="overflow: hidden"
                    >
                      <p class="mb-0 mx-2">JAY</p>
                      <p class="mx-2 mb-0 text-muted" style="font-size: 15px">
                        Tyler, what the heck do you want today?
                      </p>
                    </div>
                  </div>
                </div>

                <div class="lines_tab my-2">
                  <div class="d-flex justify-content-start align-items-start">
                    <div
                      class="
                        d-flex
                        justify-content-start
                        align-items-start
                        flex-column
                      "
                      style="overflow: hidden"
                    >
                      <p class="mb-0 mx-2">JAY</p>
                      <p class="mx-2 mb-0 text-muted" style="font-size: 15px">
                        Tyler, what the heck do you want today?
                      </p>
                    </div>
                  </div>
                </div>

                <div class="lines_tab">
                  <div class="d-flex justify-content-start align-items-start">
                    <div
                      class="
                        d-flex
                        justify-content-start
                        align-items-start
                        flex-column
                      "
                      style="overflow: hidden"
                    >
                      <p class="mb-0 mx-2">JAY</p>
                      <p class="mx-2 mb-0 text-muted" style="font-size: 15px">
                        Tyler, what the heck do you want today?
                      </p>
                    </div>
                  </div>
                </div>

                <div class="ms-2 d-flex">
                  <div class="roadmap">
                    <img src="~assets/images/roadmap2.png" alt="" />
                  </div>
                  <div class="mb-5">
                    <p class="text-center mt-3">Your line</p>
                    <div class="lines_tab ms-2 not_selected_line">
                      <div
                        class="
                          w-100
                          d-flex
                          justify-content-between
                          align-items-center
                        "
                        style="overflow: hidden"
                      >
                        <div
                          class="
                            d-flex
                            justify-content-center
                            align-items-start
                            flex-column
                          "
                        >
                          <p class="mb-0 mx-2">TYLER</p>
                          <p class="mx-2 mb-0" style="font-size: 15px">
                            I want the usual
                          </p>
                        </div>
                        <i class="fas fa-check-circle text-danger fs-4"></i>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="mb-3 ms-0 ms-lg-5">
              <p class="text-center px-2" style="width: 300px">
               You’re eliminated. You can use a second chance.
              </p>
              <button class="login2 align-items-center justify-content-center">
                Use a Second Chance
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