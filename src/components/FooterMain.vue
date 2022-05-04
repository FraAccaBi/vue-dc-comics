<template>
    <div>
        <div class="container-fluid">
            <div class="container">
                <div class="row">
                    <div class="col-4 row-cols-3">
                        <div class="col" v-for="item in cards" :key="item.id">
                            {{item.name}}
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
    </div>
</template>

<script>
export default {
  name: 'FooterMain',
  data(){
      return{
          cards: [
              {
                  id: 1,
                  name: 'DC COMICS',
                  link: 'buy-comics-digital-comics.png'
              },
              {
                  id: 2,
                  name: 'DC',
                  link: 'buy-comics-merchandise.png'
              },
              {
                  id: 3,
                  name: 'SITES',
                  link: 'buy-comics-subscriptions.png'
              },
              {
                  id: 4,
                  name: 'MERCHANDISE',
                  link: 'buy-comics-subscriptions.png'
              }
          ]
      }
  }
}
</script>

<style scoped lang="scss">

@import '~@/assets/scss/variables.scss';


</style>