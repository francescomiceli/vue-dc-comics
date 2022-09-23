<template>
  <div class="footer">
     <div class="link-list">
        <div class="content-list">
            <h3>DC COMICS</h3>
            <ul>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
            </ul>
            <h3>SHOP</h3>
            <ul>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
            </ul>
        </div>
        <div class="content-list">
            <h3>DC</h3>
            <ul>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
            </ul>
        </div>
        <div class="content-list">
            <h3>SITES</h3>
            <ul>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Games</a></li>
            </ul>
        </div>
     </div>
     <div class="logo-footer">
        <img src="../assets/img/dc-logo-bg.png" alt="logo-bg">
     </div>
  </div>
</template>

<script>
export default {
name : 'FooterComponent'
}
</script>

<style lang="scss" scoped>
.footer{
    background-image: url(../assets/img/footer-bg.jpg);
    display: flex;
    justify-content: space-around;
    color: white;
    overflow: hidden;
  }

  .logo-footer img {
    width: 100%;
    margin: -50px 0;
  }

  .link-list{
    display: flex;
    li {
        list-style-type: none;
        padding: 5px 0;
        a{
            color: white;
            text-decoration: none;
        }
        a:hover{
            text-decoration:underline;
        }
        };
    .content-list{
        padding: 20px 30px;
        h3{
            padding: 15px 0;
        }
    }    
  }
</style>