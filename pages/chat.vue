<template>
  <div>
    <div class="container mob_nav">
      <i class="fas fa-arrow-left fs-4" style="color: #f05342"></i>
      <img width="100px" src="~/assets/images/logo.png" alt="" />
      <i class="fas fa-file-alt fs-1" style="color: #f05342"></i>
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

          <div class="create_content2">
            <div class="switches">
              <button class="chat_switch2">Chat</button>
              <button class="writers_switch2">Writers</button>
            </div>

            <div class="game_will_start_in text-center w-100">
              <p class="text-muted mb-0">Game starting in</p>
              <p class="fs-2">00:12s</p>
            </div>

            <div
              class="w-100"
            >
              <div class="messages mt-4 w-100">
                <div class="msg_input my-2" style="justify-content: flex-end">
                  <p class="msg mb-0 me-2">Y'all are in for a fun game. <i class="ms-2 fas fa-times text-muted" style="cursor: pointer"></i></p>
                  <img v-b-tooltip.hover title="Tyler" src="~/assets/images/chat_user1.png" alt="" />
                </div>
                <div class="msg_input my-2" style="justify-content: flex-start">
                  <img v-b-tooltip.hover title="John Doe" src="~/assets/images/chat_user2.png" alt="" />
                  <p class="msg2 mb-0 ms-2"><i class="me-2 fas fa-times text-muted" style="cursor: pointer"></i> So we get to vote??</p>
                </div>
                <div class="msg_input my-2" style="justify-content: flex-start">
                  <img v-b-tooltip.hover title="George K." src="~/assets/images/chat_user3.png" alt="" />
                  <p class="msg2 mb-0 ms-2"><i class="me-2 fas fa-times text-muted" style="cursor: pointer"></i> ❤️ you all</p>
                </div>
                <div class="msg_input my-2" style="justify-content: flex-start">
                  <img v-b-tooltip.hover title="William Broke" src="~/assets/images/chat_user4.png" alt="" />
                  <p class="msg2 mb-0 ms-2"><i class="me-2 fas fa-times text-muted" style="cursor: pointer"></i> this is a live game</p>
                </div>
                <div class="msg_input my-2" style="justify-content: flex-end">
                  <p class="msg mb-0 me-2">yup <i class="ms-2 fas fa-times text-muted" style="cursor: pointer"></i></p>
                  <img v-b-tooltip.hover title="Tyler" src="~/assets/images/chat_user1.png" alt="" />
                </div>
                <div class="msg_input my-2" style="justify-content: flex-end">
                  <p class="msg mb-0 me-2">gonna start this soon <i class="ms-2 fas fa-times text-muted" style="cursor: pointer"></i></p>
                  <img v-b-tooltip.hover title="Tyler" src="~/assets/images/chat_user1.png" alt="" />
                </div>
                <div class="msg_input my-2" style="justify-content: flex-start">
                  <img v-b-tooltip.hover title="Jacob Mitchell" src="~/assets/images/chat_user5.png" alt="" />
                  <p class="msg2 mb-0 ms-2"><i class="me-2 fas fa-times text-muted" style="cursor: pointer"></i> Can’t wait</p>
                </div>
                <div class="msg_input my-2" style="justify-content: flex-start">
                  <img v-b-tooltip.hover title="Emma Parker" src="~/assets/images/chat_user6.png" alt="" />
                  <p class="msg2 mb-0 ms-2"><i class="me-2 fas fa-times text-muted" style="cursor: pointer"></i> My boyfriend is playing</p>
                </div>
              </div>

              <div class="write_msg">
                <i class="fas fa-link text-white"></i>
                <b-form-input
                  class="w-100 w-lg-50 text-white mx-3"
                  v-model="amount"
                  oninput="javascript: if (this.value.length > this.maxLength) this.value = this.value.slice(0, this.maxLength);"
                  placeholder="Write a message"
                  maxlength = "200"
                ></b-form-input>
                <i class="fas fa-paper-plane fs-4" style="color: #f05342; cursor: pointer"></i>
              </div>
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
