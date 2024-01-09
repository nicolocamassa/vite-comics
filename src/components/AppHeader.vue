<script>
export default {
    name: 'AppHeader',
    data(){
        return{
            links: [
                'characters',
                'comics',
                'movies',
                'tv',
                'games',
                'collectibles',
                'videos',
                'fans',
                'news',
                'shop'
            ]
        }
    }
}
</script>
<template lang="">
    <div>
        <header>
            <div class="container">
                <img src="../assets/dc-logo.png" alt="logo" class="logo">
    
                <ul>
                    <li v-for='(link, index) in links' :key='link' :class='index == 1 ? "active" : ""'>{{ link }}</li>
                </ul>
            </div>
        </header>
    </div>
</template>
<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

header{
    width: 100%;
    height: 100px;
    background-color: white;

    display: flex;
    align-items: center;
    justify-content: center;


    .container{
        width: 1200px;
        display: flex;
        justify-content: space-between;

        .logo{
            width: 70px;
        }
    
        ul{
            display: flex;
        
            li{
                list-style: none;
                margin-left: 20px;
                text-transform: uppercase;
                font-weight: 600;
                color: rgb(57, 57, 57);

                &.active,
                &:hover{
                    color: $main_color;
                    border-bottom: solid 4px $main_color;
                }
            }
        }
    }
}
</style>