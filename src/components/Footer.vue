<script>
export default {};
</script>
<template>
  <div class="container-fluid">
    <div class="container">
      <div class="row py-5">
        <div class="col-4">
          <div class="row">
            <div class="col-4">
              <div class="list-container">
                <h5 class="text-white">DC COMICS</h5>
                <ul>
                  <li>Characters</li>
                  <li>Comics</li>
                  <li>Movies</li>
                  <li>Tv</li>
                  <li>Games</li>
                  <li>Videos</li>
                  <li>News</li>
                </ul>
              </div>
              <div class="list-container">
                <h5 class="text-white">SHOP</h5>
                <ul>
                  <li>Shop DC</li>
                  <li>shop DC Collectibles</li>
                </ul>
              </div>
            </div>
            <div class="col-4">
              <div class="list-container">
                <h5 class="text-white">DC</h5>
                <ul>
                  <li>Terms Of Use</li>
                  <li>Privacy Policy (new)</li>
                  <li>Ad Choices</li>
                  <li>Advertising</li>
                  <li>Jobs</li>
                  <li>Subscriptions</li>
                  <li>Talent Workshops</li>
                  <li>CPSC Certificates</li>
                  <li>Ratings</li>
                  <li>Shop Help</li>
                  <li>Contact us</li>
                </ul>
              </div>
            </div>
            <div class="col-4">
              <div class="list-container">
                <h5 class="text-white">SITES</h5>
                <ul>
                  <li>DC</li>
                  <li>Mad Magazine</li>
                  <li>DC Kids</li>
                  <li>DC Univers</li>
                  <li>DC Power Visa</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <div class="col-2"></div>
        <div class="col-6">
          <div class="img-container">
            <img src="../assets/dc-logo-bg.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="footer-nav">
    <div
      class="container d-flex justify-content-between align-items-center py-4"
    >
      <button>SIGN-UP NOW</button>
      <div class="d-flex align-content-center gap-3">
        <h6>FOLLOW US</h6>
        <div class="icon-container">
          <img src="../assets/footer-facebook.png" alt="" />
          <img src="../assets/footer-twitter.png" alt="" />
          <img src="../assets/footer-youtube.png" alt="" />
          <img src="../assets/footer-pinterest.png" alt="" />
          <img src="../assets/footer-periscope.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container-fluid {
  background-image: url(../assets/footer-bg.jpg);
  background-size: cover;
  overflow: hidden;
}
.list-container {
  ul {
    list-style: none;
    margin-block-start: 0;
    padding-inline-start: 0;
    li {
      font-size: 12px;
      color: rgb(147, 143, 143);
    }
  }
}
.img-container {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  max-height: 300px;
  img {
    display: block;
    flex-basis: 100%;
    object-fit: contain;
  }
}
.footer-nav {
  background-color: #303030;
  button {
    background-color: #303030;
    border-color: #0282f9;
    border-style: solid;
    color: white;
    font-size: 12px;
    font-weight: 600;
    padding: 8px;
  }
  h6 {
    color: #0282f9;
    margin: 0;
    align-self: center;
  }
  .icon-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 8px;
    img {
      display: block;
      width: 100%;
    }
  }
}
</style>
