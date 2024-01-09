<script>
export default {
  name: "AppBanner",
  data() {
    return {};
  },
};
</script>
<template lang="">
  <div class="banner">
    <ul>
        <li><img src="../assets/blue_banner/buy-comics-digital-comics.png" alt=""><span>Digital comics</span></li>
        <li><img src="../assets/blue_banner/buy-comics-merchandise.png" alt=""><span>DC Merchandise</span></li>
        <li><img src="../assets/blue_banner/buy-comics-subscriptions.png" alt=""><span>Subscription</span></li>
        <li><img src="../assets/blue_banner/buy-comics-shop-locator.png" alt=""><span>comic shop locator</span></li>
        <li><img src="../assets/blue_banner/buy-dc-power-visa.svg" alt=""><span>Dc power visa</span></li>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
.banner{
    width: 100%;
    height: 140px;
    background-color: $main_color;

    ul{
        margin: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100%;
        list-style: none;

        li{
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0 60px;
            color: white;
            text-transform: uppercase;
            
            img{
                width: 50px;
                margin-right: 20px;
            }   
        }
    }
}




</style>
