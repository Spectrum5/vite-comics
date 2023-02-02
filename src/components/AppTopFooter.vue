<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<template>
    <!-- creazione template html -->
    <div class="top-footer-container">
        <div class="container-top-footer">
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics">
                <span>
                    digital comics
                </span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-merchandise.png" alt="Digital Comics">
                <span>
                    dc merchandise
                </span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="Digital Comics">
                <span>
                    subscription
                </span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="Digital Comics">
                <span>
                    comic shop locator
                </span>
            </div>
            <div>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="Digital Comics">
                <span>
                    dc power visa
                </span>
            </div>
        </div>

    </div>
</template>

<style scoped lang="scss">
/* aggiunta stile css */
.top-footer-container {
    background-color: #0282f9;
    color: white;
    padding: 70px 0 70px;

    .container-top-footer {
        width: 70%;
        margin: 0 auto;
        display: flex;
        justify-content: space-evenly;

        img {
            width: 55px;
            height: 60px;
            vertical-align: middle;
            margin-right: 10px;
        }

        span {
            text-transform: uppercase;
            vertical-align: middle;
        }
    }


}
</style>