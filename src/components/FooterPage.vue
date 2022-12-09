<!-- eslint-disable max-len -->
<template>
  <div>
    <div class="general">
      <div class="link">
        <div class="logo">
          <img
            src="../assets/images/white-logo-2.png"
            alt=""
          >
          <p>When, while lovely valley teems vapour around meande meridian sun strikes the upper impenetrable</p>
        </div>
        <ul>
          <li><h5>Quick Links</h5></li>
          <li><a href="#!">Services</a></li>
          <li><a href="#!">Contact</a></li>
          <li><a href="#!">Blog</a></li>
        </ul>

        <ul>
          <li><h5>Resources</h5></li>
          <li><a href="#!">Art Design</a></li>
          <li><a href="#!">Computer</a></li>
          <li><a href="#!">IT News</a></li>
          <li><a href="#!">Networking</a></li>
          <li><a href="#!">Web Security</a></li>
        </ul>
      </div>
      <div class="contact">
        <h5>Contact Us</h5>
        <p><span style="color:white; font-weight:bold">Addres:</span> Patricia C. Amedee 4401 Waldeck Street Grapevine Nashville, TX 76051</p>
        <p><span style="color:white; font-weight:bold">Phone:</span> +99 (0) 101 0000 888</p>
        <p><span style="color:white; font-weight:bold">Email:</span> Info@yourdomain.com</p>
      </div>
    </div>
    <div class="general2">
      <div class="copyright">
        <p style="padding: 25px;">
          &copy; 2020 Phlox. All Rights Reserved
        </p>
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
    ul{
        padding: 0 200px;
        list-style: none;
    }
    a{
        text-decoration: none;
        color: grey;
    }
    p{
        margin: 0;
        width: 300px;
        color: grey;
    }
}
.general{
    margin-top: 100px;
    padding: 50px;
    display: flex;
    justify-content: space-between;
    border-bottom: solid 2px grey;
}
.link{
    display: flex;
}
</style>
