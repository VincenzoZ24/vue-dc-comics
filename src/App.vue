<template>
  <div>
    <MenuPage/>
    <MainPage/>
    <FooterPage/>
  </div>
</template>

<script>
import MenuPage from '@/components/MenuPage.vue';
import MainPage from '@/components/MainPage.vue';
import FooterPage from '@/components/FooterPage.vue';

export default {
  components: {
    MenuPage,
    MainPage,
    FooterPage,
  },
};
</script>

<style>
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
</style>