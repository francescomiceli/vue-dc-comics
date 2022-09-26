<template>
  <div class="box-black">
    <div class="jumbotron"></div>
    <div class="section-content">
      <div class="position"><h3>CURRENT SERIES</h3></div>
      <div class="card-container" v-for="card in cards" :key="card.series">
        <img :src="card.thumb" alt="thumb">
        <p>{{card.series}}</p>
      </div>
      <div class="but">
        <button>LOAD MORE</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: 'SectionMainComponent',
props:{
  cards : Array
},
}
</script>

<style lang="scss" scoped>
.box-black{
    background-color: #1c1c1c;
    padding-bottom: 20px;
  }
  .jumbotron{
    background-image: url(@/assets/img/jumbotron.jpg);
    height: 400px;
    background-size: cover;
  }

  .section-content{
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
    padding-top: 50px;
    position: relative;
  }
  .position{
    position: absolute;
    left: 0;
    top: 0;
    transform: translate(0 , -50%);
    h3 {
        background-color: hsl(209deg 100% 49%);
        color: white;
        padding: 15px;
      }
  }
  
  .card-container{
    width: calc(100% / 6 - 20px);
    margin: 10px;
    img{
      width: 100%;
    }
  }
  .card-container:hover {
  cursor: pointer;
  opacity: 0.5;
  transform: translate(0 , -20px);
  transition: 1s;
  }
  p{
    color: white;
    text-transform: uppercase;
  }
  .but{
    text-align: center;
    width: 100%;
      button {
          background-color: hsl(209deg 100% 49%);
          color: white;
          padding: 10px 40px;
          border: none;
          text-align: center;
          cursor: pointer;
        }
  }
</style>