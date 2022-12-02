<script>
export default {};
</script>
<template>
  <div class="container-fluid bg-my-primary">
    <div class="container d-flex">
      <div class="card-container">
        <div class="img-container">
          <img src="../assets/buy-comics-digital-comics.png" alt="" />
        </div>
        <div class="text-container">DIGITAL COMICS</div>
      </div>
      <div class="card-container">
        <div class="img-container">
          <img src="../assets/buy-comics-merchandise.png" alt="" />
        </div>
        <div class="text-container">DC MERCHANDISE</div>
      </div>
      <div class="card-container">
        <div class="img-container">
          <img src="../assets/buy-comics-subscriptions.png" alt="" />
        </div>
        <div class="text-container">SUBSCRIPTION</div>
      </div>
      <div class="card-container">
        <div class="img-container">
          <img src="../assets/buy-comics-shop-locator.png" alt="" />
        </div>
        <div class="text-container">COMIC SHOP LOCATOR</div>
      </div>
      <div class="card-container">
        <div class="img-container">
          <img src="../assets/buy-dc-power-visa.svg" alt="" class="d-block" />
        </div>
        <div class="text-container">DC POWER VISA</div>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.bg-my-primary {
  background-color: #0282f9;
  margin-top: -8px;
  .container {
    justify-content: space-around;
    padding: 32px 0;
  }
}
.card-container {
  flex-basis: 20%;
  display: flex;
  justify-content: center;
  align-items: center;
  .img-container {
    flex-basis: 16%;
    img {
      display: block;
      width: 100%;
    }
  }
  .text-container {
    padding-left: 16px;
    color: white;
    font-size: 14px;
  }
}
</style>
