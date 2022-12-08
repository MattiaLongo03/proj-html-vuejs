<template>
  <div>
    <WhatWeDoVue />
    <GrowBusiness />
    <LatestWork />
    <OurPricing />
    <LatestPosts />
  </div>
</template>

<script>
import WhatWeDoVue from './WhatWeDo.vue';
import GrowBusiness from './GrowBusiness.vue';
import LatestWork from './LatestWork.vue';
import OurPricing from './OurPricing.vue';
import LatestPosts from './LatestPosts.vue';

export default {
  name: 'MainPage',
  components: {
    WhatWeDoVue,
    GrowBusiness,
    LatestWork,
    OurPricing,
    LatestPosts,
  },
};
</script>

<style lang="scss" scoped>
</style>
