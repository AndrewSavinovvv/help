<script setup>

</script>

<template>
  <header class="header container">
    <div class="header__logo">
      <img src="@/assets/icon/Logo.svg" alt="">
    </div>
    <div class="header__nav">
      <ul class="header__nav-list">
        <li>Why Alivio</li>
        <li>Solutions</li>
        <li>Community</li>
        <li>Pricing</li>
      </ul>
    </div>
    <div class="header__reg">
      <div>Sign in</div>
      <button class="header__reg-btn">
        <span>Start Trial</span>
      </button>
    </div>
  </header>
</template>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  font-family: "Lato", sans-serif;
  padding: 30px 0;
  align-items: center;
}
.header__nav-list {
  display: flex;
  gap: 72px;
  align-items: center;
}
.header__nav-list li {
  font-size: 20px;
  font-weight: 500;
  color: #000000;
}
.header__reg {
  display: flex;
  gap: 35px;
  align-items: center;
}
.header__reg div {
  font-weight: 400;
  font-size: 20px;
  color: #000000;

}
.header__reg-btn {
  padding: 13px 30px;
  background: #01996D;
  border: none;
  color: white;
  border-radius: 4px;
}
.header__reg-btn span{
  font-family: "Lato", sans-serif;
  font-size: 20px;
  font-weight: 400;
}
</style>