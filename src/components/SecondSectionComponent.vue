<template>
  <div class="logo-box">
    <div class="img-container">
        <div class="card">
         <img src="../assets/img/buy-comics-digital-comics.png" alt="">
         <span>Digital Comics</span>
        </div>
        <div class="card">
         <img src="../assets/img/buy-comics-merchandise.png" alt="">
         <span>DC Merchandise</span>
        </div>
        <div class="card">
         <img src="../assets/img/buy-comics-shop-locator.png" alt="">
         <span>Subscription</span>
        </div>
        <div class="card">
         <img src="../assets/img/buy-comics-subscriptions.png" alt="">
         <span>Comic SHop Locator</span>
        </div>
        <div class="card">
         <img src="../assets/img/buy-dc-power-visa.svg" alt="">
         <span>DC power Visa</span>
        </div>
    </div>
  </div>
</template>

<script>
export default {
name : 'SecondSectionComponent'
}
</script>

<style lang="scss" scoped>
.logo-box{
    background-color: hsl(209deg 100% 49%);
    padding: 70px 0;
   }
   .img-container{
    display: flex;
    max-width: 1200px;
    margin: 0 auto;
    justify-content: space-around;
   }
   .card{
    display: flex;
    align-items: center;
    column-gap: 15px;
    color: white;
    img{
        height: 50px;
    }
   }
   .card:hover{
    cursor: pointer;
    opacity: 0.7;
   }
</style>