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
    <div class="header-container">
        <div class="logo-header">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="nav-header">
            <ul>
                <li>
                    <a href="#">character</a>
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
                    <a href="#">collectibles</a>
                </li>
                <li>
                    <a href="#">videos</a>
                </li>
                <li>
                    <a href="#">fans</a>
                </li>
                <li>
                    <a href="#">news</a>
                </li>
                <li>
                    <a href="#">shop</a>
                </li>
            </ul>

        </div>

    </div>

</template>

<style scoped lang="scss">
/* aggiunta stile css */
.header-container {
    display: flex;
    justify-content: space-between;
    width: 65%;
    margin: 0 auto;
}

.logo-header img {
    width: 81px;
}

.nav-header {
    display: flex; 
    align-items: center;
    
    ul {
        display: flex;
        li {
            list-style-type: none;
            padding-left: 20px;
            font-size: 0.8rem;
            text-transform: uppercase;
            font-weight: bold;

            a {
                text-decoration: none;
                color: inherit;
            }
        }
    }
}

</style>