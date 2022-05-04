<template>
    <div>
        <div class="container-fluid">
            <div class="container">
                <div class="row">
                    <div class="col-4 row-cols-3">
                        <div class="col" v-for="item in cards" :key="item.id">
                            <span class="title">{{item.name}}</span>
                            <ul class="list-unstyled" >
                               <li v-for="links in item.links" :key="links.nr"> {{links.text}}</li>
                            </ul>
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
                    name: "DC Comics",
                    id: 1,
                    links: [
                        {   
                            nr:1,
                            href: "#",
                            text: "Characters",
                        },
                        {   
                            nr:2,
                            href: "#",
                            text: "Comics",
                        },
                        {   
                            nr:3,
                            href: "#",
                            text: "Movie",
                        },
                        {   
                            nr:4,
                            href: "#",
                            text: "TV",
                        },
                        {   
                            nr:5,
                            href: "#",
                            text: "Games",
                        },
                        {   
                            nr:6,
                            href: "#",
                            text: "Videos",
                        },
                        {   
                            nr:7,
                            href: "#",
                            text: "News",
                        }
                    ]
                },
                {
                    name: "DC",
                    id: 2,
                    links: [
                        {   
                            nr:1,
                            href: "#",
                            text: "Terms of Use",
                        },
                        {   
                            nr:2,
                            href: "#",
                            text: "Privacy policy (New)",
                        },
                        {   
                            nr:3,
                            href: "#",
                            text: "Ad Choise",
                        },
                        {   
                            nr:4,
                            href: "#",
                            text: "Advertising",
                        },
                        {   
                            nr:5,
                            href: "#",
                            text: "Jobs",
                        },
                        {   
                            nr:6,
                            href: "#",
                            text: "Subscription",
                        },
                        {   
                            nr:7,
                            href: "#",
                            text: "Talent Workshops",
                        },
                        {   
                            nr:8,
                            href: "#",
                            text: "CPSC Certificates",
                        },
                        {   
                            nr:9,
                            href: "#",
                            text: "Rating",
                        },
                        {   
                            nr:10,
                            href: "#",
                            text: "Shop Help",
                        },
                        {   
                            nr:11,
                            href: "#",
                            text: "Contact Us",
                        }
                    ]
                },
                {
                    name: "Sites",
                    id: 3,
                    links: [
                        {   
                            nr:1,
                            href: "#",
                            text: "DC",
                        },
                        {   
                            nr:2,
                            href: "#",
                            text: "MAD Magazine",
                        },
                        {   
                            nr:3,
                            href: "#",
                            text: "DC Kids",
                        },
                        {   
                            nr:4,
                            href: "#",
                            text: "DC Universe",
                        },
                        {   
                            nr:5,
                            href: "#",
                            text: "DC Power Visa",
                        }
                    ]
                },
                {
                    name: "Shop",
                    id: 4,
                    links: [
                        {   
                            nr:1,
                            href: "#",
                            text: "Shop DC",
                        },
                        {   
                            nr:2,
                            href: "#",
                            text: "Shop DC Collectibles",
                        }
                    ]
                }
            ]
      }
  }
}
</script>

<style scoped lang="scss">

@import '~@/assets/scss/variables.scss';


</style>