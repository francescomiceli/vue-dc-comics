<template>
  <div class="box-black">
    <div class="section-content">
        <p> --- Content goes here --- </p>
    </div>
  </div>
</template>

<script>
export default {
name: 'SectionMainComponent'
}
</script>

<style lang="scss" scoped>
  .box-black{
    background-color: black;
    padding: 50px 0;
  }
  .section-content{
    max-width: 1200px;
    margin: 0 auto;
  }
  p{
    color: white;
    font-size: 2rem;
  }
</style>