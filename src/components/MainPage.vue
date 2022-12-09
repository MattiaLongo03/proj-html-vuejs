<template>
  <div>
    <WhatWeDoVue />
    <GrowBusiness />
    <LatestWork />
    <OurPricing />
    <LatestPosts />
    <WhatPeopleSay />
    <AwesomeServices />
  </div>
</template>

<script>
import WhatWeDoVue from './WhatWeDo.vue';
import GrowBusiness from './GrowBusiness.vue';
import LatestWork from './LatestWork.vue';
import OurPricing from './OurPricing.vue';
import LatestPosts from './LatestPosts.vue';
import WhatPeopleSay from './WhatPeopleSay.vue';
import AwesomeServices from './AwesomeServices.vue';

export default {
  name: 'MainPage',
  components: {
    WhatWeDoVue,
    GrowBusiness,
    LatestWork,
    OurPricing,
    LatestPosts,
    WhatPeopleSay,
    AwesomeServices,
  },
};
</script>

<style lang="scss" scoped>
</style>
