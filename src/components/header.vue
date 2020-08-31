<template>
  <div id="header">
    <div class="logo">
      <img src="@/assets/images/fb_logo.svg" />
    </div>
    <div class="banner">
      <!-- <img src="@/assets/images/banner.png" /> -->
    </div>
  </div>
</template>

<style lang="scss">
#header {
  position: sticky;
  top: 0;
  margin: 0 auto;
  div.logo {
    padding: 10px;
    width:100%;
    background: white;
    img {
      width: 150px;
      height: auto;
    }
  }
  div.banner {
    height:147px;
    background: url('../assets/images/banner.png') no-repeat center center;
    background-size: cover;
  }
}
</style>
