<template>
    <div>
        <div class="container-fluid slider">
            <ul class="container row row-cols-5 list-unstyled">
                <li v-for="item in cards" :key="item.id">
                    <img :src="'./img/' + item.link" :key="item.id" alt="">
                     {{item.text}} 
                </li>
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
  name: 'FooterTop',
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
    padding-left: 6rem;

    li{
    color: white;
    text-transform: uppercase;
    padding: 1rem
    }
    

};
img{
    height: 50px;
}

</style>