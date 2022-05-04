<template>
    <div class="container">
        <header class="row d-flex">
            <img class="col-1 align-self-start" src="../assets/img/dc-logo.png" alt="">
            <div class="col-3"></div>
            <nav class="col-8 py-4">
                <ul class="list-unstyled text-uppercase d-flex justify-content-around">
                    <li href="item.href" v-for="item in menu" :key="item.id">{{item.text}} </li>
                </ul>
            </nav>
        </header>
    </div>
</template>

<script>
export default {
  name: 'SiteHeader',
  data(){
      return{
          menu : [
              {
                  id: 1,
                  href: '#',
                  text: 'Characters'
              },
              {
                  id: 2,
                  href: '#',
                  text: 'Comics'
              },
              {
                  id: 3,
                  href: '#',
                  text: 'Movies'
              },
              {
                  id: 4,
                  href: '#',
                  text: 'Tv'
              },
              {
                  id: 5,
                  href: '#',
                  text: 'Games'
              },
              {
                  id: 6,
                  href: '#',
                  text: 'Collectibles'
              },
              {
                  id: 7,
                  href: '#',
                  text: 'Video'
              },
              {
                  id: 8,
                  href: '#',
                  text: 'Fan'
              },
              {
                  id: 9,
                  href: '#',
                  text: 'News'
              },
              {
                  id: 10,
                  href: '#',
                  text: 'Shop'
              },
          ]
      }
  }
}
</script>

<style scoped lang="scss">

@import '~@/assets/scss/variables.scss';

.container{
  margin-top: 1.5rem  
}

li{
    padding-bottom: 1.8rem;
    border-bottom: 3px solid transparent;

    &:hover{
    color: #0c7cec;
    cursor: pointer;
    border-bottom: 3px solid $dc-primary
    }
}

</style>