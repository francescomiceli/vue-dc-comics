<template>
  <div class="social-footer">
    <div class="but-foot">
        <button>SIGN-UP NOW!</button>
    </div>
    <div class="icon-social">
        <h3>FOLLOW US</h3>
        <img src="../assets/img/footer-facebook.png" alt="">
        <img src="../assets/img/footer-periscope.png" alt="">
        <img src="../assets/img/footer-pinterest.png" alt="">
        <img src="../assets/img/footer-twitter.png" alt="">
        <img src="../assets/img/footer-youtube.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
name : 'SecondFooterComponent'
}
</script>

<style lang="scss" scoped>
.social-footer{
    background-color: hsl(240deg 1% 19%);
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 30px 0;
   }

   .but-foot button{
    color: white;
    border: 2px solid hsl(209deg 100% 49%);
    padding: 10px 15px;
    background-color: hsl(240deg 1% 19%);
    margin-right: 240px;
   }

   button:hover{
    cursor: pointer;
    opacity: 0.7;
   }

   .icon-social{
    display: flex;
    align-items: center;
    h3{
        color: hsl(209deg 100% 49%);
        padding: 0px 20px;
    };
    img{
        padding: 0px 10px;
    }
   }
   .icon-social img:hover{
    cursor: pointer;
    opacity: 0.7;
   }
</style>