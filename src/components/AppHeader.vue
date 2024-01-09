<script>
export default {
    name: 'AppHeader',
    data(){
        return{
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
                    <li>CHARATCERS</li>
                    <li>MATTIA</li>
                    <li>CIAPE</li>
                </ul>
            </div>
        </header>
    </div>
</template>
<style lang="scss" scoped>
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
                margin-right: 10px;
            }
        }
    }
}
</style>