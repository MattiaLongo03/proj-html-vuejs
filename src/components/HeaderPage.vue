<!-- eslint-disable max-len -->
<template>
  <div>
    <div class="container pt-3">
      <header>
        <img
          src="../assets/images/white-logo-2.png"
          alt=""
        >
        <nav>
          <ul>
            <li>Home</li>
            <li>About</li>
            <li>Services</li>
            <li>Blog</li>
            <li>Contact</li>
            <li>Portfolio</li>
          </ul>
          <button id="blue">
            Sign In
          </button>
        </nav>
      </header>
    </div>
    <div class="container business">
      <div class="container business-testo">
        <h2>Business Planning Digital Technology Modern Solution !</h2>
        <p id="sub">
          When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper surface
        </p>
        <button
          id="red"
          style="margin-right:10px"
        >
          Try it Now
        </button>
        <button id="blue">
          Explore More
        </button>
      </div>
      <img
        id="desk"
        src="../assets/images/header.png"
        alt=""
      >
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderPage',
};
</script>

<style lang="scss" scoped>
*{
  color: white;
  background-color: #030636;
}

header{
  display: flex;
  align-items: center;
  justify-content: space-between;

  nav{
    display: flex;
  }
  ul{
    margin: 0 50px;
    display: flex;
    list-style: none;
  }

  li{
    font-weight: bold;
    padding: 10px;
    display: flex;
    cursor: pointer;
  }

  li:hover{
    color: #DA466C;
  }
}

.business{
  display: flex;
  align-items: center;
  height: 500px;

  .business-testo{
    margin-left: 0;
    width: 350px;
    #sub{
      margin: 30px 0 ;
      width: 400px;
      color: #03A7D3E6;
    }
  }

  #desk{
    width: 500px;
  }
}
</style>
