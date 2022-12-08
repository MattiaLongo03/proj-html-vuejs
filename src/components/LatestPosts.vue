<!-- eslint-disable max-len -->
<template>
  <div>
    <div class="container-testo">
      <p style="color: #F9636B">
        Blog
      </p>
      <p style="font-size: 30px">
        <span style="font-weight:bold">Latest</span> Posts
      </p>
      <p>When, while lovely valley teems with vapour around meand the meridian sun strikes the upper surface</p>
    </div>
    <div class="container schede">
      <div class="scheda-pc">
        <div class="testo">
          <p>April, 2019 . by Paul</p>
          <h6>Amazon gets CCI nod to acquire 49% stake in</h6>
          <p>When, while lovely valley teems with vapour around meand the meridian sun s...</p>
          <button>Read More</button>
        </div>
      </div>
      <div class="scheda">
        <div class="testo-2">
          <p>April, 2019 . by Paul</p>
          <p style="font-weight:bold">
            Clearing Corporations get SEBI to invest in overnight funds
          </p>
          <p>When, while lovely valley teems with vapour around meand the meridian sun s...</p>
          <button>Read More</button>
        </div>
      </div>
      <div class="scheda">
        <div class="testo-2">
          <p>April, 2019 . by Paul</p>
          <p>Shabnam Dhillon, wife of RSSB chief Gurinder Dhillon, passes away in London</p>
          <p>When, while lovely valley teems with vapour around meand the meridian sun s...</p>
          <button>Read More</button>
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
button{
    padding: 20px;
    border: none;
    border-radius: 50px;
}
.container-testo{
    margin-top: 100px;
    text-align: center;
}
.container{
    margin-top: 100px;
    display: flex;
    justify-content: space-between;
}
.scheda-pc{
    width: 1000px;
    background-image: url(../assets/images/headway-537308-unsplash-1380x703.jpg);
    background-size: cover;
    color: white;
    border-radius: 25px;
    .testo{
        padding: 200px 25px 20px;
    }
}
.scheda{
    margin-left: 50px;
    background-color: #030636;
    color: white;
    border-radius: 25px;
    .testo-2{
        padding: 50px;
    }
}
</style>
