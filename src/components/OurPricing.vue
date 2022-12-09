<!-- eslint-disable max-len -->
<template>
  <div>
    <div class="container-titolo">
      <p style="color: #F9636B">
        Price List
      </p>
      <h2>Our Pricing</h2>
      <p>When, while the lovely valley teems with vapour aorund meand the merdian sun strikes the upper surface.</p>
      <div class="container schede">
        <div class="scheda">
          <h2>Designing</h2>
          <p>PROCESS</p>
          <p>$</p>
          <h1>40</h1>
          <p>Per Month</p>
          <p><span style="font-weight:bold">Creative</span> Design Enabled</p>
          <p><span style="font-weight:bold">Vibrant</span> Color Usage</p>
          <p><span style="font-weight:bold">Eye</span> Catching Design</p>
          <p><span style="font-weight:bold">Extreme</span> Typography</p>
          <p><span style="font-weight:bold">Exceptional</span> Design</p>
          <button id="red">
            Order Now
            <font-awesome-icon icon="fa-solid fa-arrow-right" />
          </button>
        </div>
        <div class="schedared">
          <h2>Developing</h2>
          <p>PRODUCT</p>
          <p>$</p>
          <h1>60</h1>
          <p>Per Month</p>
          <p><span style="font-weight:bold">Creative</span> Design Enabled</p>
          <p><span style="font-weight:bold">Vibrant</span> Color Usage</p>
          <p><span style="font-weight:bold">Eye</span> Catching Design</p>
          <p><span style="font-weight:bold">Extreme</span> Typography</p>
          <p><span style="font-weight:bold">Exceptional</span> Design</p>
          <button
            id="red"
            style="background-color:white; color:#F9636B"
          >
            Order Now
            <font-awesome-icon icon="fa-solid fa-arrow-right" />
          </button>
        </div>
        <div class="scheda">
          <h2>Supporting</h2>
          <p>CLIENTS</p>
          <p>$</p>
          <h1>80</h1>
          <p>Per Month</p>
          <p><span style="font-weight:bold">Creative</span> Design Enabled</p>
          <p><span style="font-weight:bold">Vibrant</span> Color Usage</p>
          <p><span style="font-weight:bold">Eye</span> Catching Design</p>
          <p><span style="font-weight:bold">Extreme</span> Typography</p>
          <p><span style="font-weight:bold">Exceptional</span> Design</p>
          <button id="red">
            Order Now
            <font-awesome-icon icon="fa-solid fa-arrow-right" />
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
.container-titolo{
    margin-top: 100px;
    padding-bottom: 100px;
    text-align: center;
    background-color: #030636;
    color: white;
}
.schede{
    display: flex;
    justify-content: space-between;
    text-align: center;
}
.scheda{
    color: black;
    padding: 50px;
    background-color: white;
    border-radius: 30px;
}
.schedared{
    padding: 50px;
    background-color: #F9636B;
    color: white;
    border-radius: 30px;
}
</style>
