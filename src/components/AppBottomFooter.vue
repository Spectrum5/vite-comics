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

            <a class="my-button" href="#">sign-up now!</a>

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

        .my-button {
	        border:1px solid #0282f9;
            color:#ffffff;
            font-size:15px;
            padding:12px;
            margin: 10px 0 10px;
            cursor:pointer;
            .my-button:hover {
	            background-color:black;
            }
        }      
        .social-footer {
            display: flex;
            align-items: center;
            color: white;

            span {
                color: #0282f9;
            }

            ul {
                display: flex;

                li {
                    list-style-type: none;
                    margin-left: 15px;

                }
            }
        }
    }
}

    
</style>