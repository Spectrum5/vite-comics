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
    <div class="container-bottom">
        <div class="bottom-container">
            <button type="button">
                <a href="#">Sign-up</a>
            </button>
            <div class="social-footer">
                <span>FOLLOW US</span>
                <ul>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-facebook.png" alt="Facebook">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-twitter.png" alt="Facebook">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-youtube.png" alt="Facebook">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-pinterest.png" alt="Facebook">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-periscope.png" alt="Facebook">
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
    /* aggiunta stile css */
.container-bottom {
    background-color: #303030;
    .bottom-container {
    width: 70%;
    margin: 0 auto;
    background-color: #303030;
    display: flex;
    justify-content: space-between;

        .register-footer {
            

        }
        
        .social-footer {
            display: flex;
            color: white;

            ul {
                display: flex;

                li {
                    list-style-type: none;

                }
            }
        }
    }
}

    
</style>