<template>
    <div class="container-fluid">
        <header class="row d-flex">
            <img class="col-1 align-self-center" src="../assets/img/dc-logo.png" alt="">
            <div class="col-3"></div>
            <nav class="col-8 pt-5">
                <ul class="list-unstyled text-uppercase d-flex justify-content-around">
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Collectibles</li>
                    <li>Videos</li>
                    <li>Fans</li>
                    <li>News</li>
                    <li>Shop</li>
                </ul>
            </nav>
        </header>
    </div>
</template>

<script>
export default {
  name: 'SiteHeader',
}
</script>

<style scoped lang="scss">
.container-fluid{
  margin-top: -3rem  
}
</style>