<template>
  <div>
    <div class="mob_nav align-items-center justify-content-center">
      <img width="100px" src="~/assets/images/logo.png" alt="" />
    </div>

    <b-navbar
      class="navbar px-5"
      toggleable="lg"
      type="transparent"
      variant="transparent"
    >
      <b-navbar-brand>
        <NuxtLink to="/">
          <img width="100px" src="~/assets/images/logo.png" alt="" />
        </NuxtLink>
      </b-navbar-brand>

      <b-navbar-toggle class="text-white" target="nav-collapse"
        ><i class="fas fa-bars fs-4 text-white"></i
      ></b-navbar-toggle>

      <b-collapse id="nav-collapse" class="mx-auto" is-nav>
        <b-navbar-nav class="ms-auto mb-2 mb-lg-0">
          <b-nav-item class="mx-2">
            <NuxtLink to="/home" class="text-white">Home </NuxtLink>
          </b-nav-item>

          <b-nav-item class="mx-2">
            <NuxtLink to="/aboutus" class="text-white">About Us </NuxtLink>
          </b-nav-item>

          <b-nav-item class="mx-2">
            <NuxtLink to="/" class="text-white">Contact Us </NuxtLink>
          </b-nav-item>

          <b-nav-item class="mx-2">
            <NuxtLink to="/terms" class="text-white">
              Terms & Conditions
            </NuxtLink>
          </b-nav-item>

          <b-nav-item class="mx-2">
            <NuxtLink to="/privacypolicy" class="text-white">
              Privacy Policy
            </NuxtLink>
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ms-auto mb-2 mb-lg-0">
          <NuxtLink to="/">
            <button class="login me-3 mb-2">Login</button>
          </NuxtLink>
          <NuxtLink to="/signup">
            <button class="signup me-3 mb-2">Sign Up</button>
          </NuxtLink>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>

    <div class="bg2 pt-5">
      <div class="mx-3 mx-lg-5 mx-md-5 w-100" style="margin-top: 120px">
        <p class="pb-2 pb-lg-5 fs-5 w-100 text-center">About Us</p>
        <div class="mx-3 mx-lg-0 abt_cards">
          <div class="col-12 col-md-12 col-lg-5 abt_1 m-4">
            <p class="fw-bold">We are committed to protecting your privacy</p>
            <p>
              We collect the minimum amount of information about you that is
              commensurate with providing you with a satisfactory service. This
              policy indicates the type of processes that may result in data
              being collected about you. Your use of this website gives us the
              right to collect that information.
            </p>
            <p>Information Collected</p>
            <p>
              We may collect any or all of the information that you give us
              depending on the type of transaction you enter into, including
              your name
            </p>
          </div>

          <div
            class="col-12 col-md-12 col-lg-5 abt_2 m-4"
            style="border-radius: 14px"
          >
            <img width="100%" src="~/assets/images/about1.png" alt="" />
          </div>

          <div
            class="col-12 col-md-12 col-lg-5 abt_2 m-4"
            style="border-radius: 14px"
          >
            <img width="100%" src="~/assets/images/about2.png" alt="" />
          </div>

          <div class="col-12 col-md-12 col-lg-5 abt_1 m-4">
            <p class="fw-bold">We are committed to protecting your privacy</p>
            <p>
              We collect the minimum amount of information about you that is
              commensurate with providing you with a satisfactory service. This
              policy indicates the type of processes that may result in data
              being collected about you. Your use of this website gives us the
              right to collect that information.
            </p>
            <p>Information Collected</p>
            <p>
              We may collect any or all of the information that you give us
              depending on the type of transaction you enter into, including
              your name
            </p>
          </div>
        </div>
      </div>

      <div class="mt-5 mb-5">
        <p class="fs-2 text-center">Our Team</p>
        <div
          class="mt-5 w-100 d-flex justify-content-center align-items-center flex-wrap"
        >
          <div
            class="mx-2 d-flex justify-content-center align-items-center flex-column"
          >
            <img src="~assets/images/team1.png" alt="" />
            <p class="mb-0">Tyler</p>
            <img class="team_bg" src="~assets/images/team_bg.png" alt="" />
          </div>
          <div
            class="mx-2 d-flex justify-content-center align-items-center flex-column"
          >
            <img src="~assets/images/team2.png" alt="" />
            <p class="mb-0">Tyler</p>
            <img class="team_bg" src="~assets/images/team_bg.png" alt="" />
          </div>
          <div
            class="mx-2 d-flex justify-content-center align-items-center flex-column"
          >
            <img src="~assets/images/team3.png" alt="" />
            <p class="mb-0">Tyler</p>
            <img class="team_bg" src="~assets/images/team_bg.png" alt="" />
          </div>
          <div
            class="mx-2 d-flex justify-content-center align-items-center flex-column"
          >
            <img src="~assets/images/team4.png" alt="" />
            <p class="mb-0">Tyler</p>
            <img class="team_bg" src="~assets/images/team_bg.png" alt="" />
          </div>
        </div>
      </div>

      <img class="outer_poly1" src="~/assets/images/outer_polygon1.svg" alt="" />
      <img class="outer_poly2" src="~/assets/images/outer_polygon2.svg" alt="" />
      <img class="outer_poly3" src="~/assets/images/outer_polygon3.svg" alt="" />
      <img class="outer_poly4" src="~/assets/images/outer_polygon4.svg" alt="" />

      <img class="mob_poly1" src="~/assets/images/mob_Polygon1.svg" alt="" />
      <img class="mob_poly2" src="~/assets/images/mob_polygon2.svg" alt="" />
      <img class="mob_poly3" src="~/assets/images/mob_polygon3.svg" alt="" />
      <img class="mob_poly4" src="~/assets/images/mob_polygon4.svg" alt="" />
    </div>
  </div>
</template>
