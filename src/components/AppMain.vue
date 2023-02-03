<script>
import AppList from './AppList.vue';

export default {
    data() {
        return {

        }
    },
    components:{
        AppList,
    }
}
</script>

<template>
    <!-- creazione template html -->
    <div class="container">
        <div class="jumbotron">
        </div>
        <div class="content-main">
            <div class="film-main">
                <AppList/>
            </div>
        </div>
    </div>

</template>

<style scoped lang="scss">
    /* aggiunta stile css */
.container {
    

    .jumbotron {
        height: 400px;
        background-image: url(../assets/img/jumbotron.jpg);
        height: 400px;
    }

    .content-main {
        background-color: #1c1c1c;
        .film-main {
            width: 70%;
            margin: 0 auto;
        }
    }
}
</style>