<template>
  <div class="container">
    <nav class="d-flex justify-content-between align-items-center w-100">
      <div class="logo-container">
        <img src="../assets/dc-logo.png" alt="" class="d-block" />
      </div>
      <ul class="link-list d-flex">
        <li v-for="link in navArray">
          <a href="#">{{ link }}</a>
        </li>
      </ul>
    </nav>
  </div>
</template>
<script>
export default {
  data() {
    return {
      navArray: [
        "CHARACTERS",
        "COMICS",
        "MOVIES",
        "TV",
        "GAMES",
        "COLLECTIBLES",
        "VIDEOS",
        "FANS",
        "NEWS",
        "SHOP",
      ],
    };
  },
};
</script>
<style scoped lang="scss">
nav {
  height: 80px;
}
.logo-container {
  width: 5%;
  padding: 8px 0;
  img {
    width: 100%;
  }
}
.link-list {
  list-style: none;
  justify-content: space-between;
  margin-block: 0;
  padding-inline-start: 0;
  column-gap: 24px;
  a {
    text-decoration: none;
    color: black;
    font-size: 12px;
    padding: 26px 0;
    font-weight: 600;
    &:hover {
      color: #0282f9;
      border-bottom: 4px solid #0282f9;
    }
  }
}
</style>
