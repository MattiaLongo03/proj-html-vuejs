<template>
  <div>
    <div class="container">
      <div class="testo">
        <p style="color:#F9636B">
          Portfolio
        </p>
        <p><span style="font-weight:bold">Latest</span> work</p>
      </div>
      <div class="frecce">
        <div class="freccia-sinistra">
          <font-awesome-icon icon="fa-solid fa-arrow-left" />
        </div>
        <div class="freccia-destra">
          <font-awesome-icon icon="fa-solid fa-arrow-right" />
        </div>
      </div>
    </div>
    <div class="immagini">
      <div class="container-immagine-testo">
        <div class="immagine">
          <img
            src="../assets/images/84316050-0af0-49db-a53a-241d47ddad0e-2-790x576.jpg"
            alt=""
          >
          <div class="testo">
            <p style="font-weight:bold">
              Basket of Flower on table
            </p>
          </div>
        </div>
      </div>
      <div class="container-immagine-testo">
        <div class="immagine">
          <img
            src="../assets/images/8wa60okr-1-790x576.jpg"
            alt=""
          >
          <div class="testo">
            <p style="font-weight:bold">
              Purinky Products
            </p>
          </div>
        </div>
      </div>
      <div class="container-immagine-testo">
        <div class="immagine">
          <img
            src="../assets/images//a247b00b-3621-470f-b4b8-b3ac46f25907-1-790x576.jpg"
            alt=""
          >
          <div class="testo">
            <p style="font-weight:bold">
              Satisfy Poster
            </p>
          </div>
        </div>
      </div>
      <div class="container-immagine-testo" />
      <div class="immagine">
        <img
          src="../assets/images/DRY-1-790x576.jpg"
          alt=""
        >
        <div class="testo">
          <p style="font-weight:bold">
            Mock Up
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

</script>

<style lang="scss" scoped>
img{
    width: 200px;
}
.container{
    margin-top: 50px;
    display: flex;
    justify-content: space-between;
}
.frecce{
    color: #F9636B;
    display: flex;
    align-items: center;
}
.freccia-sinistra{
    display: flex;
    align-items: center;
    justify-content: center;
    margin-right: 20px;
    padding: 5px;
    border: 1px solid #F9636B;
    border-radius: 50%;
    width: 50px;
    height: 50px;
}
.freccia-destra{
    display: flex;
    align-items: center;
    justify-content: center;
    margin-right: 20px;
    padding: 5px;
    border: 1px solid #F9636B;
    border-radius: 50%;
    width: 50px;
    height: 50px;
}
.immagini{
    display: flex;
    justify-content: space-between;
}

</style>
