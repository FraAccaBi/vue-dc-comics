<template>
    <div>
        <div class="container-fluid slider">
            <div class="container row row-cols-5">
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
        </div>
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
}
</script>

<style scoped lang="scss">
.slider{
    background-color: #0c7cec
}
.slider-text{
    color: white;
    text-transform: uppercase;
}

</style>