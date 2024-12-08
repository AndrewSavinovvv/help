<template>
  <div class="steps container">
    <div class="steps_block">
      <div class="step__header">
        <span>01</span>
        <div class="header-text">Personalize</div>
      </div>
      <p>
        Answer a quick survey about how you express yourself, what causes you stress, and what area would you like to work on. This way, we can fully personalize your journal!
      </p>
      <img src="@/assets/img/Rectangle%2030.png" alt="">
    </div>
    <div class="steps_block">
      <div class="step__header">
        <span>01</span>
        <div class="header-text">Personalize</div>
      </div>
      <p>
        Answer a quick survey about how you express yourself, what causes you stress, and what area would you like to work on. This way, we can fully personalize your journal!
      </p>
      <img src="@/assets/img/Rectangle%2030.png" alt="">
    </div>
    <div class="steps_block">
      <div class="step__header">
        <span>01</span>
        <div class="header-text">Personalize</div>
      </div>
      <p>
        Answer a quick survey about how you express yourself, what causes you stress, and what area would you like to work on. This way, we can fully personalize your journal!
      </p>
      <img src="@/assets/img/Rectangle%2030.png" alt="">
    </div>
  </div>
</template>

<style scoped>
.steps {
  display: flex;
  gap: 95px;
  padding-bottom: 330px;
}

.steps_block {
  position: relative;
}

.step__header {
  position: relative;
}

.step__header span {
  color: #01996D33;
  font-size: 150px;
  font-weight: 400;
  font-family: Georgia, serif;
  position: relative;
  z-index: 1;
}

.header-text {
  color: #000000;
  font-weight: 700;
  font-size: 30px;
  font-family: Georgia, serif;
  position: absolute;
  top: 108px;
  left: 90px;
  z-index: 0;
}
.steps_block img {
  margin-top: 60px;
}
.steps_block p {
  color: #424242;
  font-size: 20px;
  font-weight: 500;
  font-family: "Lato", sans-serif;
  line-height: 30px;
}
.steps_block:nth-child(2) {
  position: relative;
  top: 300px;
}
.steps_block:nth-child(3) {
  position: relative;
  top: 40px;
}
</style>
