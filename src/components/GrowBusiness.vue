<!-- eslint-disable max-len -->
<template>
  <div>
    <div class="container grow">
      <img
        src="../assets/images/men-data.png"
        alt=""
      >
      <div class="testo">
        <p>Start Your Project</p>
        <h2>Grow Your Business With Our Strategy</h2>
        <p style="color: #03A7D3E6">
          When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper surface of the impenetrable follage of my trees, and bur a few stray gleams steal into the inner sanctuary
        </p>
        <button
          id="red"
          style="margin-right: 10px"
        >
          Try It Now
        </button>
        <button id="blue">
          Explore More
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
*{
    color: white;
    background-color: #030636;
}
.grow{
    margin: 0;
    padding-top: 50px;
    display: flex;
    align-items: center;
    img{
        margin-left: 50px;
        padding: 50px;
        background-image: url(../assets/images/nemoodar.png);
        background-size: 325px;
        background-repeat: no-repeat;
        width: 400px;
    }
    .testo{
        margin-left: 100px;

    }
}
</style>
