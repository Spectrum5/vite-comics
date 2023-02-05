<script>
import AppList from './AppList.vue';

export default {
    data() {
        return {

        }
    },
    components: {
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
                <AppList />
            </div>
            <div class="current-series">
                <span>current series</span>
            </div>
            <div class="button-main">
                <button type="button" class="button">load more</button>
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
        background-repeat: no-repeat;
        background-size: cover;
    }

    .content-main {
        background-color: #1c1c1c;
        position: relative;

        .current-series {
            position: absolute;
            margin-left: 20%;
            background-color: #0282f9;
            color: white;
            padding: 15px 25px 15px 25px;
            top: -4%;
            text-transform: uppercase;
            font-weight: bold;
        }

        .film-main {
            width: 70%;
            margin: 0 auto;
        }
        .button-main {
            display: flex;
            justify-content: center;
            padding-bottom: 20px;
            .button {
                text-align: center;
                color: #FFFFFF;
                background-color: #0282f9;
                padding: 10px 50px;
                border: 1px solid #006FE6;
                cursor: pointer;
                text-transform: uppercase;
                font-weight: bold;
            }

            .button:hover {
                background-color: #0063CC;
                border-color: #0056B3;
            }
        }
    }
}
</style>