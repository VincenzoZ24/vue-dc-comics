<template>
  <nav>
    <img class="logo" src="@/img/dc-logo.png" alt="">
    <ul class="list">
      <li>CHARACTERS</li>
      <li>COMICS</li>
      <li>MOVIES</li>
      <li>TV</li>
      <li>GAMES</li>
      <li>COLLECTIBLES</li>
      <li>VIDEOS</li>
      <li>FANS</li>
      <li>NEWS</li>
      <li>SHOP</li>
    </ul>
  </nav>
</template>

<script>

export default {
};

</script>

<style lang="scss" scoped>
.logo{
  width: 70px;
  object-fit: contain;
}
nav{
  max-width: 1200px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 2rem;
}
.list{
  display: flex;
  gap: 1rem;
  li{
    list-style: none;
  }
}
</style>