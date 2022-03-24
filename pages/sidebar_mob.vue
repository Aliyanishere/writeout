<template>
  <div>
    <div class="container sidebar_nav">
      <i class="fas fa-arrow-left fs-2" style="color: #f05342"></i>
      <div class="d-flex flex-column justify-content-center align-items-center">
        <img src="~/assets/images/user_icon.svg" alt="" />
        <div class="d-flex justify-content-center align-items-center">
          <img class="mt-2 me-1" src="~/assets/images/coin.svg" alt="" />
          <p class="mb-0 mt-2" style="color: #e7a52e">2500</p>
        </div>
      </div>
      <i class="ms-2 fas fa-comments-alt fs-1" style="color: #f05342"></i>
    </div>

    <div class="bg2" style="padding-top: 150px">
      <NuxtLink to="/writeout_shop">
        <div class="mob_sidebar">
          <p class="mb-0 ms-3">Writeout Shop</p>
        </div>
      </NuxtLink>
      <NuxtLink to="/aboutus">
        <div class="mob_sidebar">
          <p class="mb-0 ms-3">Contact Support</p>
        </div>
      </NuxtLink>
      <NuxtLink to="/storyline">
        <div class="mob_sidebar">
          <p class="mb-0 ms-3">Join the Discord</p>
        </div>
      </NuxtLink>
      <NuxtLink to="/terms">
        <div class="mob_sidebar">
          <p class="mb-0 ms-3">Terms of Service</p>
        </div>
      </NuxtLink>
      <NuxtLink to="/privacypolicy">
        <div class="mob_sidebar">
          <p class="mb-0 ms-3">Privacy Poilicy</p>
        </div>
      </NuxtLink>
      <NuxtLink to="/chat">
        <div class="mob_sidebar">
          <p class="mb-0 ms-3">Rate App</p>
        </div>
      </NuxtLink>
      <NuxtLink to="/profile">
        <div class="mob_sidebar">
          <p class="mb-0 ms-3">Settings</p>
        </div>
      </NuxtLink>
      <NuxtLink to="/">
        <div class="mob_sidebar">
          <p class="mb-0 ms-3">Sign Out</p>
        </div>
      </NuxtLink>

      <p class="w-100 ps-3">Version 0.1.1 b1</p>

      <img class="mob_poly1" src="~/assets/images/mob_Polygon1.svg" alt="" />
      <img class="mob_poly2" src="~/assets/images/mob_polygon2.svg" alt="" />
      <img class="mob_poly3" src="~/assets/images/mob_polygon3.svg" alt="" />
      <img class="mob_poly4" src="~/assets/images/mob_polygon4.svg" alt="" />
    </div>
  </div>
</template>
