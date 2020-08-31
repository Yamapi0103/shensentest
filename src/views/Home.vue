<template>
  <div id="home">
    <Header></Header>
    <div class="wrap">
      <div class="block">
        <div class="no-text header"></div>
        <div class="icon_text_wrap">
          <img class="white_menu02" src="@/assets/images/white_menu_02.svg" />
          <p>
            多張保單地址 / 電話 /
            <br>Email變更
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import Header from "@/components/header";
  export default {
    components: {
      Header,
    },
  };
</script>
<style lang="scss">
#home {
  height: 100vh;
}
.wrap {
  margin: 0 auto;
  width: 1200px;
  background: white;
  display: flex;
  align-items: center;
  justify-content: start;
  padding: 50px;
  box-shadow: 0px 5px 5px #888;
  .block {
    border: 2px solid #008795;
    border-radius: 0 0 5px 5px;
    .no-text.header {
      height: 10px;
      background: #008795;
    }
    .icon_text_wrap {
      display: flex;
      border-bottom: 1px solid #008795;
      margin: 15px;
      img.white_menu02 {
        width: 50px;
      }
    }
  }
}
</style>