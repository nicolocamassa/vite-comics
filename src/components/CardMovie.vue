<script>
export default {
    name: 'CardMovie',
    props: {
        film: Object
    }
};
</script>

<template lang="html">
    <div class="card" :key="index">
        <img :src='film.thumb' alt="">
        <div class="film-title">
            {{ film.series }}
        </div>
    </div>
</template>

<style lang="scss" scoped>
.card {
    width: calc(100% / 6);
    margin: 50px 0;

    img {
        width: 200px;
        height: 300px;
        margin-bottom: 10px;
    }

    .film-title {
        text-transform: uppercase;
        padding-right: 40px;
    }
}
</style>
