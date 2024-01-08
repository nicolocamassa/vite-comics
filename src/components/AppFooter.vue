<script>
export default {
  name: "AppFooter",
  data() {
    return {};
  },
};
</script>
<template lang="">
  <div class="footer-container">
    <div class="container">
        <div class="menu-list">
            <div class="column">
                <ul>
                    <li>DC COMICS</li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
    
                <ul>
                    <li>SHOP</li>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>

            <div class="column">
                <ul>
                    <li>DC</li>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>

            <div class="column">
                <ul>
                    <li>SITES</li>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>

        </div>
    
        <div class="background-logo"></div>
    </div>
  </div>
</template>
<style lang="scss">
.footer-container {
    display: flex;
    justify-content: center;
    width: 100%;
    background-image: url(../assets/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;

    .container{
        justify-content: space-between;
    }

    .menu-list{
        display: flex;
        flex-wrap: wrap;

        .column{
            height: 100%;
            margin-right: 10px;

            ul{
                color: grey;
                list-style: none;
                line-height: 1.8;
        
                li:nth-child(1){
                    color: rgb(255, 255, 255);
                    font-size: 24px;
                    margin-bottom: 8px;
                    font-weight: 600;
                }
            }
        }
    }

}

.background-logo{
    width: 50%;
    height: 100%;
    background-image: url(../assets/dc-logo-bg.png);
    background-repeat: no-repeat;
}
</style>
