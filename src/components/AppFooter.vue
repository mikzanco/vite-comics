<script>
export default {
  name: 'AppFooter',
  // data(){
  //   return{
  //     immagine
  //   }
  // }
}
</script>

<template>
  <footer>
    <img src="../assets/img/dc-logo-bg.png" alt="" class="logo">
    <div class="sectionone">
        <div class="container ">

          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          <a href="#">digital comics</a>
          <img src="../assets/img/buy-comics-merchandise.png" alt="">
          <a href="#">dc merchandise</a>
          <img src="../assets/img/buy-comics-shop-locator.png" alt="">
          <a href="#">subscription</a>
          <img src="../assets/img/buy-comics-subscriptions.png" alt="">
          <a href="#">Comic shop locator</a>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="">
          <a href="#">DC power visa</a>

      </div>
    </div>
      
    <div class="containerBig ">
      
      <div class="sectiontwo">
        <div class="container">
          <ul> <h4>Dc comics</h4>
            <li>Character</li>
            <li>Character</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
          
          <ul><h4>Shop</h4>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
          
          <ul><h4>Dc</h4>
            <li>Terms Of Use</li>
            <li>Pricacy pollicy(New)</li>
            <li>Ad Choise</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent Workshop</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>
          
          <ul> <h4>Sites</h4>
            <li>DC</li>
            <li>Mad Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>           
          </ul>
        </div>
        
      </div>
      <div class="sectionthree">
        <div class="container">
          <div class="button">
            <button class="btn">Sign-up now!</button>
          </div>
          <div class="social d-flex">
            <h4>Follow Us</h4>
            <img src="../assets/img/footer-facebook.png" alt="">
            <img src="../assets/img/footer-periscope.png" alt="">
            <img src="../assets/img/footer-pinterest.png" alt="">
            <img src="../assets/img/footer-twitter.png" alt="">
            <img src="../assets/img/footer-youtube.png" alt="">
          </div>
        </div>
        
      </div>
    </div>
  </footer>
</template>


// background-image: url("../assets/img/dc-logo-bg.png")
<style lang="scss" scoped>

  @use '../style/partials/variables' as *;
  @use '../style/partials/mixin' as *;
  
  footer{
    height: 620px;
    width: 100%;
    background-image: url("../assets/img/footer-bg.jpg");
    color: white;
    overflow: hidden;
    position: relative;
    .logo{
      position: absolute;
      right: 10%
    }
    .sectionone{
      height: 130px;
      width: 100%;
      background-color: $primary-color;
      display: flex;
      align-items: center;
      justify-content: center;
      a{
        text-decoration: none;
        color: white;
      }
      img{
        height: 110px;
        padding: 30px;
      }
      
    }
    .sectiontwo{
      height: 370px;
      width: 100%;
      display: flex;
      .container{
        margin: 0 auto;
        justify-content: flex-start;
      }
      ul{
        padding: 20px;
        list-style: none;
        li{
          padding: 5px;
          color: #9a9a9a;
        }
      }
    }
    .sectionthree{
      height: calc(620px - 130px - 370px);
      width: 100%;
      background-color: #050505;
      display: flex;
      align-items: center;
      justify-content: center;
      
      .container{
        
         justify-content: space-between;
        h4{
          color: $primary-color;
          font-size: 1.5rem;
          padding: 15px;
        }
          .social img{
          padding: 10px
        }
        .btn{
          padding: 16px 32px;
          text-align: center;
          font-size: 16px;
          text-transform: uppercase;
          margin: 4px 2px;
          cursor: pointer;
          background-color: #050505;
          color: $primary-color;
          border: 2px solid $primary-color;
          &:hover{
            background-color: $primary-color;
            color: #050505;
          }
        }

      }
      
    }
    
    

  }
</style>