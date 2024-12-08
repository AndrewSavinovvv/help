<script setup>

</script>

<template>
  <div class="product container">
    <div class="product__left">
      <div class="product__left-img">
        <img src="@/assets/img/Image.png" alt="">
      </div>
      <div class="product__left__submenu">
        <div class="product__left__submenu-title">
          <span>Customized For</span>
        </div>
        <div class="product__left__submenu-line"></div>
        <div class="product__left__submenu-avatar">
          <img src="@/assets/img/img.png" alt="">
        </div>
        <div class="product__left__submenu__name">
          <span>Mikayla</span>
        </div>
        <div class="product__left__submenu-info">
            <h3>Your custom contents</h3>
          <h4>• Understand Your Stress</h4>
          <h4>• Anger Management</h4>
        </div>
      </div>
    </div>
    <div class="product__right">
      <div class="product__right-title">
        <h6>Our product</h6>
      </div>
      <div class="product__right-subtitle">
        <h1> You tell us your stress,<br>
          We make your diary</h1>
      </div>
      <div class="product__right-text">
        <p>Everyone experiences it, and in different ways.
          Let Alivio guide you, in a personalized journal experience, to overcome your stress.</p>
      </div>
      <div class="">
        <button class="product__right-btn">Find Your Way</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.product{
  display: flex;
  padding-top: 120px;
  gap: 86px;
  position: relative;
  margin-bottom: 126px;
}
.product__right {
  display: flex;
  flex-direction: column;
}
.product__right-title h6{
  color: #424242;
  font-size: 25px;
  font-weight: 600;
  font-family: "Lato", sans-serif;
  line-height: 39px;
}
.product__right-subtitle h1 {
  color: #01996D;
  font-size: 50px;
  font-weight: 700;
  font-family: Georgia,sans-serif;
}
.product__right-text p {
  font-size: 20px;
  font-weight: 400;
  font-family: "Lato", sans-serif;
  line-height: 31px;
  color: #484848;
  margin-bottom: 40px;
}
.product__right-btn {
  background: #01996D;
  border-radius: 4px;
  border: none;
  font-size: 20px;
  font-weight: 400;
  color: white;
  padding: 20px 50px;
  cursor: pointer;
  font-family: "Lato", sans-serif;
}
.product__left__submenu {
  display: flex;
  flex-direction: column;
  align-items: center;
  background: #fafafa;
  border-radius: 4px;
  position: absolute;
  bottom: -100px;
  left: -55px;
  width: 296px;
  height: 260px;
  padding-top: 22px;
  box-shadow: 0 3px 18px #A5A5A540;
}
.product__left__submenu-title span {
  font-size: 14px;
  font-family: "Lato", sans-serif;
  font-weight: 600;
  color: #000000;
}
.product__left__submenu-line {
  background: #000000;
  width: 110px;
  height: 1px;
  margin-bottom: 13px;
  margin-top: 7px;
}
.product__left__submenu-avatar {
  margin-bottom: 10px;
}
.product__left__submenu__name {
  color: #000000;
  font-size: 12px;
  font-weight: 400;
  font-family: "Lato", sans-serif;
  line-height: 18px;
}
.product__left__submenu-info h3 {
  font-weight: 700;
  font-size: 16px;
  font-family: Georgia,sans-serif;
  margin-bottom: 16px;
}
.product__left__submenu-info {
  margin-top: 20px;
}
.product__left__submenu-info h4 {
  font-size: 10px;
  font-family: "Lato", sans-serif;
  font-weight: 400;
  line-height: 16px;
  margin-bottom: 16px;
}
</style>