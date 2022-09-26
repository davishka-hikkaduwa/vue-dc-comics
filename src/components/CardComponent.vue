<template>
    <div class="card">
        <img :src="card.thumb" :alt="card.series">
        <div class="title">
            {{ card.series }}
        </div>
    </div>
</template>

<script>
    export default {
        name: 'CardComponent',
        props: {
            card: Object,
        }
    };
</script>

<style scoped lang="scss">
.card{
    padding: 20px;
    display: flex;
    flex-direction: column;
    img{
        height: 170px;
        object-fit: cover;
        object-position: top;
    }
    .title{
        padding-top: 15px;
        text-transform: uppercase;
    }
}
</style>