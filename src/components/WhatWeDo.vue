<!-- eslint-disable max-len -->
<template>
  <div>
    <div class="title">
      <p style="color: #F9636B">
        Our Services
      </p>
      <p style="font-size: 40px">
        <span style="font-weight:bold">What</span> We Do
      </p>
      <p style="margin-bottom: 100px">
        When, while the lovely valley teems with vapour around meand the
      </p>
    </div>
    <div class="options">
      <div class="option">
        <img
          src="../assets/images/Group-247.png"
          alt=""
        >
        <h3>Data Analysis</h3>
        <p>When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper</p>
      </div>
      <div class="option">
        <img
          src="../assets/images/Group-567.png"
          alt=""
        >
        <h3>SEO optimization</h3>
        <p>When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper</p>
      </div>
      <div class="option">
        <img
          src="../assets/images/Group-538.png"
          alt=""
        >
        <h3>Security Data</h3>
        <p>When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper</p>
      </div>
      <div class="option">
        <img
          src="../assets/images/Group-566.png"
          alt=""
        >
        <h3>Branding Strategy</h3>
        <p>When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper</p>
      </div>
    </div>
    <div class="button">
      <button id="red">
        View All Services
      </button>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
p{
    margin: 0;
}

.title{
    margin-top: 30px;
    text-align: center;
}

.options{
    display: flex;
    align-items: center;
    justify-content: space-around;
    img {
        width: 100px;
    }
    .option{
        text-align: center;
        width: 200px;
        h3{
            margin: 30px 0;
            font-weight: bold;
        }

    }
}

.button{
    margin: 150px 0 50px 0;
    display: flex;
    justify-content: center;
    #red{
        color: white;
        padding: 5px 30px;
        background-color: #DA466C;
        border: none;
        border-radius: 25px;
    }
}

</style>
