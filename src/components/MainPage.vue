<template>
  <div>
    <WhatWeDoVue />
    <GrowBusiness />
    <LatestWork />
  </div>
</template>

<script>
import WhatWeDoVue from './WhatWeDo.vue';
import GrowBusiness from './GrowBusiness.vue';
import LatestWork from './LatestWork.vue';

export default {
  name: 'MainPage',
  components: {
    WhatWeDoVue,
    GrowBusiness,
    LatestWork,
  },
};
</script>

<style lang="scss" scoped>
</style>
