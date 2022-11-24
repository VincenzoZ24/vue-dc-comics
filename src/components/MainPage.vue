<template>
  <main>
    <section class="content"></section>
    <section class="content_blue">
      <div>
       <img src="@/img/buy-dc-power-visa.svg" alt="">
      </div>
      <div>
        <img src="@/img/buy-comics-subscriptions.png" alt="">
      </div>
      <div>
        <img src="@/img/buy-comics-shop-locator.png" alt="">
      </div>
      <div>
        <img src="@/img/buy-comics-merchandise.png" alt="">
      </div>
      <div>
        <img src="@/img/buy-comics-digital-comics.png" alt="">
      </div>
    </section>
  </main>
</template>

<script>
export default {
};
</script>

<style lang="scss" scoped>
main{
  max-width: 1200px;
}
.content{
  width: 100%;
  height: 10rem;
  background-color: black;
}
.content_blue{
  width: 100%;
  height: 10rem;
  background-color: blue;
  display: flex;
  justify-content: space-between;
  div{
    width: calc((1200px - 4rem) / 5);
    display: flex;
    img{
      width: 100%;
      object-fit: contain;
    }
  }
}
</style>