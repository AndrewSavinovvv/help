<script setup>

</script>

<template>
  <div class="hero-wrapper ">
    <div class="hero container">
    <h1>
      Be aware, <br>
      Manage well.
    </h1>
      <p>
        Everyone experiences stress in different ways. <br>
        Let Alivio guide you, in a personalized journal <br> experience, to overcome your stress.
      </p>
      <button class="hero__btn">
        Find Your Way
      </button>
    </div>
  </div>
</template>

<style scoped>
.hero-wrapper {
  background: url("@/assets/img/BG.png");
}
.hero {
  height: 895px;
  display: flex;
  justify-content: center;
  align-items: flex-start;
  flex-direction: column;
}
.hero h1 {
  color: #01996D;
  font-size: 65px;
  font-weight: 700;
  font-family: Georgia, serif;
}
.hero p {
  color: #484848;
  font-size: 20px;
  font-weight: 400;
  font-family: "Lato", sans-serif;
}
.hero__btn {
  background: #01996D;
  color: white;
  border: none;
  border-radius: 4px;
  padding: 20px 50px;
  cursor: pointer;
  font-family: "Lato", sans-serif;
  font-size: 20px;
  font-weight: 400;
}
</style>