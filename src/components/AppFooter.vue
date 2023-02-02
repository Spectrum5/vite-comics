<script>
import AppTopFooter from "./AppTopFooter.vue"

export default {
    components: {
        AppTopFooter,
    },

    data() {
        return {

        }
    }
}
</script>

<template>
    <!-- creazione template html -->
    <div class="footer-main-container">
        <AppTopFooter />
        <div class="footer-flex">
            <div class="footer-main">
                <div class="list-footer">
                    <h3>
                        dc comics
                    </h3>
                    <ul>
                        <li>
                            <a href="#">characters</a>
                        </li>
                        <li>
                            <a href="#">comics</a>
                        </li>
                        <li>
                            <a href="#">movies</a>
                        </li>
                        <li>
                            <a href="#">tv</a>
                        </li>
                        <li>
                            <a href="#">games</a>
                        </li>
                        <li>
                            <a href="#">videos</a>
                        </li>
                        <li>
                            <a href="#">news</a>
                        </li>
                    </ul>
                </div>
                <div class="list-footer">
                    <h3>
                        shop
                    </h3>
                    <ul>
                        <li>
                            <a href="#">characters</a>
                        </li>
                        <li>
                            <a href="#">comics</a>
                        </li>

                    </ul>
                </div>

            </div>

            <div class="footer-main">
                <div class="list-footer">
                    <h3>
                        dc
                    </h3>
                    <ul>
                        <li>
                            <a href="#">terms of use</a>
                        </li>
                        <li>
                            <a href="#">privacy policy (new)</a>
                        </li>
                        <li>
                            <a href="#">ad choices</a>
                        </li>
                        <li>
                            <a href="#">advertising</a>
                        </li>
                        <li>
                            <a href="#">jobs</a>
                        </li>
                        <li>
                            <a href="#">subscriptions</a>
                        </li>
                        <li>
                            <a href="#">talent workshops</a>
                        </li>
                        <li>
                            <a href="#">CPSC certificates</a>
                        </li>
                        <li>
                            <a href="#">ratings</a>
                        </li>
                        <li>
                            <a href="#">shop help</a>
                        </li>
                        <li>
                            <a href="#">contact us</a>
                        </li>
                    </ul>
                </div>

            </div>

            <div class="footer-main">
                <div class="list-footer">
                    <h3>
                        sites
                    </h3>
                    <ul>
                        <li>
                            <a href="#">DC</a>
                        </li>
                        <li>
                            <a href="#">MAD magazine</a>
                        </li>
                        <li>
                            <a href="#">DC kids</a>
                        </li>
                        <li>
                            <a href="#">DC universe</a>
                        </li>
                        <li>
                            <a href="#">DC power visa</a>
                        </li>
                    </ul>
                </div>

            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
/* aggiunta stile css */
.footer-main-container {
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    .footer-flex {
        display: flex;
        width: 70%;
        margin: 0 auto;
        background-image: url(../assets/img/dc-logo-bg.png);
        background-repeat: no-repeat;
        background-position: right;
        .footer-main {
            margin-right: 50px;
            .list-footer {
                h3 {
                    text-transform: uppercase;
                    margin: 30px 0 10px;
                    color: white;
                }

                ul {

                    li {
                        list-style-type: none;
                        font-size: 0.8rem;
                        text-transform: capitalize;
                        font-weight: bold;
                        padding-bottom: 8px;

                        a {
                            text-decoration: none;
                            color: #797979;
                        }
                    }
                }
            }
        }
    }
}
</style>