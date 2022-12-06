<template>
  <div>
    <WhatWeDoVue />
    <GrowBusiness />
  </div>
</template>

<script>
import WhatWeDoVue from './WhatWeDo.vue';
import GrowBusiness from './GrowBusiness.vue';

export default {
  name: 'MainPage',
  components: {
    WhatWeDoVue,
    GrowBusiness,
  },
};
</script>

<style lang="scss" scoped>
</style>
