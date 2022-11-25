<template>
  <div class="card">
    <div class="contents">
      <img class="img_card" :src="img" alt="" />
      <h5>{{ title }}</h5>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardPage',
  props: {
    img: {
      type: String,
    },
    title: {
      type: String,
    },
  },
};
</script>

<style lang="scss" scoped>
.contents{
    width: calc((1200px - 11rem) / 6);
    color: white;
    margin-bottom: 2rem;
}
img{
    width: 100%;
}
</style>