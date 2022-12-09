<!-- eslint-disable max-len -->
<template>
  <div>
    <div class="container">
      <div class="testo">
        <h1>We Offer Awesome Services</h1>
        <p>Whe, while lovely teems with vapour around meand meridian sun strikes the upper surface.</p>
      </div>
      <div class="form">
        <label for="address">
          <input
            id=""
            type="email"
            name="Address"
            placeholder="Enter your Email Address"
          >
          <button id="blue">Subscribe</button>
        </label>
      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
.container{
  margin-top: 100px;
  padding: 50px;
  display: flex;
  align-items: center;
  background-color: #F9636B;
  color: white;
  border-radius: 15px;
}
.testo{
  margin-right: 100px;
}
.form{
  padding: 5px;
  background-color: white;
  border-radius: 25px;
  input{
    font-size: 15px;
    padding: 0 120px 0 20px;
    border: none;
  }
  ::placeholder{
    color: lightgrey;
    font-style: italic;
  }
}
</style>
