<template>
  <div>
    <WhatWeDoVue />
    <GrowBusiness />
    <LatestWork />
    <OurPricing />
  </div>
</template>

<script>
import WhatWeDoVue from './WhatWeDo.vue';
import GrowBusiness from './GrowBusiness.vue';
import LatestWork from './LatestWork.vue';
import OurPricing from './OurPricing.vue';

export default {
  name: 'MainPage',
  components: {
    WhatWeDoVue,
    GrowBusiness,
    LatestWork,
    OurPricing,
  },
};
</script>

<style lang="scss" scoped>
</style>
