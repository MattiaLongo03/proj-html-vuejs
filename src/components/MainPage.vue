<template>
  <div>
    <WhatWeDoVue />
    <GrowBusiness />
    <LatestWork />
    <OurPricing />
    <LatestPosts />
    <WhatPeopleSay />
  </div>
</template>

<script>
import WhatWeDoVue from './WhatWeDo.vue';
import GrowBusiness from './GrowBusiness.vue';
import LatestWork from './LatestWork.vue';
import OurPricing from './OurPricing.vue';
import LatestPosts from './LatestPosts.vue';
import WhatPeopleSay from './WhatPeopleSay.vue';

export default {
  name: 'MainPage',
  components: {
    WhatWeDoVue,
    GrowBusiness,
    LatestWork,
    OurPricing,
    LatestPosts,
    WhatPeopleSay,
  },
};
</script>

<style lang="scss" scoped>
</style>
