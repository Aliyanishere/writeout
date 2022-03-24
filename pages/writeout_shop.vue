<template>
  <div>
    <div class="container mob_nav">
      <i class="fas fa-bars fs-1" style="color: #f05342"></i>
      <img width="90px" src="~/assets/images/logo.png" alt="" />
      <div class="d-flex flex-column justify-content-center align-items-center">
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
            Restore all purchases
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
          <p class="mb-1 fs-5">Writeout Shop</p>
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
            <div class="tabs active">
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
            <div class="for_hide">
              <b-form-input
                class="text-white m-2"
                v-model="text"
                placeholder="Enter Game Code"
                style="width: 300px"
              ></b-form-input>
              <button class="login2 setup m-2">
                Join Game <i class="fas fa-arrow-right text-white"></i>
              </button>
              <div class="mb-0 create_a_game mt-3 mt-lg-0">
                <p class="mb-0">
                  Or <span class="text-danger">Create a New Game</span>
                </p>
              </div>
            </div>

            <div class="mt-4">
              <p class="mb-0 ms-3">App Icons</p>
              <div class="games ms-3 mt-3">
                <div class="public_games me-3">
                  <img src="~assets/images/app_icon1.png" alt="" />
                  <p class="mb-0 mt-2">Default</p>
                </div>

                <div class="public_games me-3">
                  <img src="~assets/images/app_icon2.png" alt="" />
                  <p class="mb-0 mt-2">
                    <img src="~assets/images/coin.png" alt="" /> 250
                  </p>
                </div>

                <div class="public_games me-3">
                  <img src="~assets/images/Rectangle.png" alt="" />
                  <p class="mb-0 mt-2">Default</p>
                </div>

                <div class="public_games me-3">
                  <img src="~assets/images/app_icon1.png" alt="" />
                  <p class="mb-0 mt-2">Default</p>
                </div>

                <div class="public_games me-3">
                  <img src="~assets/images/app_icon2.png" alt="" />
                  <p class="mb-0 mt-2">
                    <img src="~assets/images/coin.png" alt="" /> 250
                  </p>
                </div>
              </div>
            </div>

            <div class="mt-5">
              <p class="mb-1 ms-3">Tokens</p>
              <p class="mb-0 ms-3 text-muted" style="font-size: 15px">
                Tokens can be won for free by participating in app. They unlock
                various cosmetic features and abilities.
              </p>
              <div class="games ms-3 mt-3">
                <div class="post_games me-3">
                  <p class="mb-1 mt-2">
                    <img class="me-1" src="~assets/images/coin.png" alt="" />
                    500 tokens
                  </p>
                  <p class="text-danger mb-2">$2.99</p>
                  <button
                    class="add_new mt-0"
                    style="display: flex; justify-content: center; align-items:center; width: 150px"
                  >
                    Buy
                  </button>
                </div>

                <div class="post_games me-3">
                  <p class="mb-1 mt-2">
                    <img class="me-1" src="~assets/images/coin.png" alt="" />
                    1250 tokens
                  </p>
                  <p class="text-danger mb-2">$4.99</p>
                  <button
                    class="add_new mt-0"
                    style="display: flex; justify-content: center; align-items:center; width: 150px"
                  >
                    Buy
                  </button>
                </div>

                <div class="post_games me-3">
                  <p class="mb-1 mt-2">
                    <img class="me-1" src="~assets/images/coin.png" alt="" />
                    500 tokens
                  </p>
                  <p class="text-danger mb-2">$2.99</p>
                 <button
                    class="add_new mt-0"
                    style="display: flex; justify-content: center; align-items:center; width: 150px"
                  >
                    Buy
                  </button>
                </div>

                <div class="post_games me-3">
                  <p class="mb-1 mt-2">
                    <img class="me-1" src="~assets/images/coin.png" alt="" />
                    500 tokens
                  </p>
                  <p class="text-danger mb-2">$2.99</p>
                 <button
                    class="add_new mt-0"
                    style="display: flex; justify-content: center; align-items:center; width: 150px"
                  >
                    Buy
                  </button>
                </div>
              </div>
            </div>

            <div class="mt-5">
              <p class="mb-1 ms-3">Second Chances</p>
              <div class="games ms-3 mt-3">
                <div class="post_games me-3">
                  <p class="mb-1 mt-2">
                    <img
                      class="me-1"
                      src="~assets/images/second_chance.png"
                      alt=""
                    />
                    1 Second Chance
                  </p>
                  <p class="text-danger mb-2">$0.99</p>
                 <button
                    class="add_new mt-0"
                    style="display: flex; justify-content: center; align-items:center; width: 150px"
                  >
                    Buy
                  </button>
                </div>

                <div class="post_games me-3">
                  <p class="mb-1 mt-2">
                    <img
                      class="me-1"
                      src="~assets/images/second_chance.png"
                      alt=""
                    />
                    3 Second Chance
                  </p>
                  <p class="text-danger mb-2">$4.99</p>
                 <button
                    class="add_new mt-0"
                    style="display: flex; justify-content: center; align-items:center; width: 150px"
                  >
                    Buy
                  </button>
                </div>

              </div>
            </div>

            <div class="mt-5">
              <p class="mb-1 ms-3">Extra Lives</p>
              <div class="games ms-3 mt-3">
                <div class="post_games me-3">
                  <p class="text-white mb-0"><i class="fas fa-heart text-danger me-2"></i> 1 Extra Life</p>
                  <p class="mb-2 mt-2">
                    <img class="me-1" src="~assets/images/coin.png" alt="" />
                    550
                  </p>
                  <button
                    class="add_new mt-0"
                    style="display: flex; justify-content: center; align-items:center; width: 150px"
                  >
                    Buy
                  </button>
                </div>

                <div class="post_games me-3">
                  <p class="text-white mb-0"><i class="fas fa-heart text-danger me-2"></i> 3 Extra Lives</p>
                  <p class="mb-2 mt-2">
                    <img class="me-1" src="~assets/images/coin.png" alt="" />
                    5800
                  </p>
                  <button
                    class="add_new mt-0"
                    style="display: flex; justify-content: center; align-items:center; width: 150px"
                  >
                    Buy
                  </button>
                </div>

                <div class="post_games me-3">
                  <p class="text-white mb-0"><i class="fas fa-heart text-danger me-2"></i> 3 Extra Lives</p>
                  <p class="mb-2 mt-2">
                    <img class="me-1" src="~assets/images/coin.png" alt="" />
                    5800
                  </p>
                  <button
                    class="add_new mt-0"
                    style="display: flex; justify-content: center; align-items:center; width: 150px"
                  >
                    Buy
                  </button>
                </div>

              </div>
            </div>

            <div class="mt-5 mb-4">
              <p class="mb-1 ms-3">Additional Abilities</p>
              <div class="games ms-3 mt-3">
                <div class="post_games me-3">
                  <div class="d-flex justify-content-between align-items-center w-100 mb-3">
                    <p class="mb-1 mt-2 ms-2">
                      <i class="fas fa-lock me-2"></i>
                      Remove all ads
                    </p>
                    <p class="text-danger mb-0">$4.99</p>
                  </div>
                 <button
                    class="add_new mt-0"
                    style="display: flex; justify-content: center; align-items:center; width: 270px"
                  >
                    Buy
                  </button>
                </div>
              </div>
            </div>

            <div>
              <button
              class="restore mb-4"
              >
              Restore all purchases
              <i class="fas fa-times"></i>
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
