<template>
  <div>
    <HeaderPage />
    <MainPage />
    <FooterPage />
  </div>
</template>

<script>
import HeaderPage from '@/components/HeaderPage.vue';
import MainPage from '@/components/MainPage.vue';
import FooterPage from '@/components/FooterPage.vue';

export default {
  name: 'App',
  components: {
    HeaderPage,
    MainPage,
    FooterPage,
  },
};
</script>

<style lang="scss">
#red{
  padding: 5px 30px;
  background-color: #DA466C;
  border-radius: 25px;
  border: none;
  color: white;
}
#blue{
  padding: 5px 30px;
  background-color: #1466A1;
  border-radius: 25px;
  border: none;
  color: white;
}
@import "~bootstrap/scss/bootstrap";
</style>
