<template>
    <div class="container-fluid">
        <div class="container">
            <div class="row row-cols-2">
                <div class="col"></div>
                <div class="col d-flex justify-content-evenly align-items-center">
                    <span>Follow us</span>
                    <div v-for="item in cards" :key="item.id">
                        <img :src="'./img/' + item.link" alt="">
                    </div>
                </div>
            </div>
        </div>
                
    </div>
</template>

<script>
export default {
  name: 'FooterBottom',
  data(){
      return{
          cards: [
              {
                  id: 1,
                  title: 'Facebook',
                  link: 'footer-facebook.png'
              },
              {
                  id: 2,
                  title: 'Twitter',
                  link: 'footer-twitter.png'
              },
              {
                  id: 3,
                  title: 'Youtube',
                  link: 'footer-youtube.png'
              },
              {
                  id: 4,
                  title: 'Pinterest',
                  link: 'footer-pinterest.png'
              },
              {
                  id: 5,
                  title: 'Periscope',
                  link: 'footer-periscope.png'
              },

          ]
      }
  }
}
</script>

<style scoped lang="scss">

@import '~@/assets/scss/variables.scss';

.container-fluid{
    padding: 1.5rem;
    height: 80px;
    background-color:  $footer-bottom;
}
span{
    color: $dc-primary;
    text-transform: uppercase;
    font-weight: 900;
}
img{
    height: 30px;
}


</style>