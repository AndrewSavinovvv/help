<script setup>

</script>

<template>
  <div class="media">
    <div class="media__block container">
      <div class="media__block-left">
        <h1>Let's hear about <br> Kayla's success story</h1>
        <p>See how well Alivio works in a real customer’s life. </p>
        <button class="media__block-left-btn">Let’s get started</button>
      </div>
      <div class="media__block-right">
        <img src="@/assets/img/Video.png" alt="">
      </div>
    </div>
  </div>
</template>

<style scoped>
.media {
  background: #245852;
}
.media__block {
  display: flex;
  align-items: center;
  justify-content: center;
  padding-top: 229px;
  gap: 31px;
  padding-bottom: 176px;
}
.media__block-left h1 {
  color: #FFFFFF;
  font-size: 50px;
  font-family: Georgia, serif;
  font-weight: 700;
  line-height: 78px;
  margin-bottom: 33px;
}
.media__block-left p {
  font-size: 25px;
  font-weight: 600;
  font-family: "Lato", sans-serif;
  line-height: 39px;
  color: white;
  margin: 0;
  margin-bottom: 57px;
}
.media__block-left, .media__block-right {
  width: 50%;
}
.media__block-left-btn {
  font-size: 20px;
  background: #01996D;
  border: none;
  padding: 20px 50px;
  color: white;
  border-radius: 4px;
  cursor: pointer;
}
</style>