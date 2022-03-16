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
      <b-navbar-brand href="#">
        <img width="100px" src="~/assets/images/logo.png" alt="" />
      </b-navbar-brand>

      <b-navbar-toggle class="text-white" target="nav-collapse"
        ><i class="fas fa-bars fs-4 text-white"></i
      ></b-navbar-toggle>

      <b-collapse id="nav-collapse" class="mx-auto" is-nav>
        <b-navbar-nav class="mx-auto mb-2 mb-lg-0">
          <b-nav-item href="https://writeout.netlify.app/" class="mx-2"
            >Home</b-nav-item
          >
          <b-nav-item href="https://writeout.netlify.app/aboutus" class="mx-2"
            >Reports</b-nav-item
          >
          <b-nav-item href="https://writeout.netlify.app/terms" class="mx-2"
            >Metrics</b-nav-item
          >
        </b-navbar-nav>
      </b-collapse>

      <b-collapse id="nav-collapse" class="mx-auto" is-nav>
        <b-navbar-nav
          class="ms-auto mb-2 mb-lg-0 d-flex justify-content-center align-items-center"
        >
          <p class="text-white me-2 mt-3">@Koala23</p>
          <img src="~/assets/images/user_icon.svg" alt="" />
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>

    <div class="bg2" style="display:flex; justify-content: center; align-items: center; flex-direction: row; flex-wrap: wrap">
      
      <div class="manage_user col-12 col-md-12 col-lg-3 px-3">
        <div class="mt-3 ms-3 d-flex justify-content-start align-items-center">
          <i class="fas fa-arrow-left fs-4 me-3" style="color: #f05342"></i>
          <p class="mb-0 fs-5">Manage User</p>
        </div>

        <div
          class="mt-5 d-flex justify-content-start align-items-center flex-column"
        >
          <div
            class=" d-flex justify-content-center align-items-center"
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

          <div class="setup mt-3 mb-5">
            <button
              class="login2 mb-0 mt-0"
              style="display: flex; justify-content: center; width: 260px; background-color: #C91A07; border: none"
            >
              Revoke Admin
            </button>
            <button
              class="login2 mt-2 mb-2"
              style="display: flex; justify-content: center; width: 260px; background-color: #5215BE; border: none"
            >
              Grant Mod
            </button>
            <button
              class="login2 mt-2 mb-2"
              style="display: flex; justify-content: center; width: 260px"
            >
              Unverify User
            </button>
          </div>
        </div>
      </div>

      <div class="user_stats col-12 col-md-12 col-lg-5 px-3">
          <div class="pt-0 pt-lg-3 manage_middle">

              <div class="properties">
                <p>User ID</p>
                <p>12902913829</p>
              </div>

              <div class="properties">
                <p>UID</p>
                <p>Ibk1527CUFmc</p>
              </div>

              <div class="properties">
                <p>Full Name</p>
                <p>Bilbo Baggins</p>
              </div>

              <div class="properties">
                <p>Password</p>
                <p class="text-danger">Send Reset</p>
              </div>

              <div class="properties">
                <p>User Tags</p>
                <p class="d-flex">
                    <button class="verify_btn">VERIFIED</button>
                    <button class="mod_btn">MOD</button>
                    <button class="staff_btn">STAFF</button>
                </p>
              </div>

              <div class="properties">
                <p>IP Address</p>
                <p class="text-danger">192.168.1.1</p>
              </div>

              <div class="properties">
                <p>Fingerprint</p>
                <p class="text-danger">Ibk1527CUFmcnjLwIs4A9</p>
              </div>

              <div class="properties">
                <p>Created</p>
                <p>8 Feb 2020 10:43:22 am</p>
              </div>

              <div class="properties">
                <p>Last Online</p>
                <p>10 Mar 2022 12:02:22 pm</p>
              </div>

              <div class="properties">
                <p>User Status</p>
                <p>Active <button class="ban_btn ms-2">Ban</button></p>
              </div>

              <div class="properties">
                <p>Email Verified</p>
                <p><label class="switch">
                    <input type="checkbox">
                    <span class="slider round"></span>
                  </label>
                </p>
              </div>

              <div class="properties">
                <p>Global Opt Out</p>
                <p><label class="switch">
                  <input type="checkbox" checked>
                  <span class="slider round"></span>
                  </label>
                </p>
              </div>

          </div>

          <Field />

          <div class="d-flex py-2">
              <b-form-input
                class="for_place text-white my-2"
                v-model="text"
                placeholder="Give coins"
                style="width: 120px"
              ></b-form-input>
              <button class="send setup m-2">
                Send
              </button>
          </div>

          <div class="sending_btns mb-5">
              <button
                 class="login2 m-2 m-md-2 m-lg-0"
                 style="display: flex; justify-content: center; width: 250px">
                 <i class="me-2 fas fa-heart"></i>
                 Send Extra Life
               </button>
              <button 
                class="login2 mx-2"
                style="display: flex; justify-content: center; width: 260px">
                <img class="me-2" src="~assets/images/second_chance.png" alt="">
                Send Second Chance
              </button>
          </div>
      </div>

      <div class="user_detail col-12 col-md-12 col-lg-4 px-3 px-lg-5 mb-5">
          <div class="d-flex justify-content-between align-items-start">
              <p>
                  jessica <br>
                  <span class="text-muted">Viewed profile</span>
              </p>
              <p>09/22/2022</p>
          </div>

          <div class="d-flex justify-content-between align-items-start">
              <p>
                 notkoala <br>
                 <span class="text-muted">If user writes in we have told them no more dirty stories about adult content.</span>
              </p>
              <p>09/22/2022</p>
          </div>

          <Field />

          <div class="mt-4">
              <div class="d-flex justify-content-between align-items-start">
                  <p>Reported Content</p>
                  <p class="text-danger">View</p>
              </div>

              <div class="d-flex justify-content-between align-items-start">
                  <p>Change Log</p>
                  <p class="text-danger">View</p>
              </div>

              <div class="d-flex justify-content-between align-items-start">
                  <p>Purchases</p>
                  <p class="text-danger">View</p>
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
