<template>
    <div>
        <div class="container-fluid slider">
            <ul class="container row row-cols-5 list-unstyled">
                <li v-for="item in cards" :key="item.id">
                    <img class="h-100 w-50" :src="'~@/assets/img/' + item.link" :key="item.id" alt="">
                     {{item.text}} 
                </li>
                <div class="digital col">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <div class="slider-text">Digital Comics</div>
                </div>
                <div class="merchandise col">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <div class="slider-text">DC Merchandise</div>
                </div>
                <div class="subscription col">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <div class="slider-text">Subscription</div>
                </div>
                <div class="shops col">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <div class="slider-text">Comic shop locator</div>
                </div>
                <div class="visa col">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <div class="slider-text">dc power visa</div>
                </div>
            </ul>
        </div>
        <div class="main_footer">
            
        </div>
        <div class="footer">
            <div class="call_to_action"></div>
            <div class="social"></div>
        </div>
        
    </div>
</template>

<script>
export default {
  name: 'SiteFooter',
  data(){
      return{
          cards: [
              {
                  id: 1,
                  text: 'Digital comics',
                  link: 'buy-comics-digital-comics.png'
              },
              {
                  id: 2,
                  text: 'DC Merchandise',
                  link: 'buy-comics-merchandise.png'
              },
              {
                  id: 3,
                  text: 'Subscription',
                  link: 'buy-comics-subscriptions.png'
              },
              {
                  id: 4,
                  text: 'Comic shop locator',
                  link: 'buy-comics-shop-locator.png'
              },
              {
                  id: 5,
                  text: 'DC power Visa',
                  link: 'buy-dc-power-visa.svg'
              },

          ]
      }
  }
}
</script>

<style scoped lang="scss">

@import '~@/assets/scss/variables.scss';

.slider{
    background-color: $dc-primary;

    .slider-text{
    color: white;
    text-transform: uppercase;
    }
    

};
img{
    height: 50px;
}

</style>