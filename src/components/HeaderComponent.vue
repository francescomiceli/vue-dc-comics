<template>
  <div class="content">
    <div>
        <img src="../assets/img/dc-logo.png" alt="dc-logo">
    </div>
    <div>
        <ul class="list">
            <li><a href="">Characters</a></li>
            <li><a href="">Comics</a></li>
            <li><a href="">Movie</a></li>
            <li><a href="">Tv</a></li>
            <li><a href="">Games</a></li>
            <li><a href="">Coolection</a></li>
            <li><a href="">Videos</a></li>
            <li><a href="">Fans</a></li>
            <li><a href="">News</a></li>
            <li><a href="">Shop</a></li>
        </ul>
    </div>
  </div>
</template>

<script>
export default {
name : 'HeaderComponent'
}
</script>

<style lang="scss" scoped>
.content{
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 0;
    .list{
        display: flex;
        list-style-type: none;
        li{
            padding: 0px 15px;
            a{
                text-decoration: none;
                color: black;
                text-transform: uppercase;
            }
            a:hover{
                color: hsl(209deg 100% 49%);
                text-decoration: underline;
            }
        }
        
    }
   }
</style>