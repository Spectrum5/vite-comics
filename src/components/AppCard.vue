<script>
export default {
    name: 'AppCard',
    data() {
        return {
        }
    },
    props: {
        img: String,
        title: String
    }
}
</script>

<template>
    <div class="card">
        <img :src="img" :alt="title">
        <a href="#"><h4>{{ title }}</h4></a>
    </div>
</template>

<style lang="scss" scoped>
.card {
    color: white;
    text-align: center;

    h4 {
        margin-top: 10px;
    }
}

</style>