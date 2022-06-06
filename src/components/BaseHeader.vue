<template>
    <header class="header">
        <div class="container">
            <div class="header__inner">
                <div class="header__logo">
                    <img src="../assets/img/dc-logo.png">
                </div>
                <nav class="navigation">
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">movies</a></li>
                        <li><a href="#">tv</a></li>
                        <li><a href="#">games</a></li>
                        <li><a href="#">colectiblers</a></li>
                        <li><a href="#">videos</a></li>
                        <li><a href="#">fans</a></li>
                        <li><a href="#">news</a></li>
                        <li><a href="#">shop</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
</template>



<script>
export default{
    name: 'BaseHeader',

}


</script>

<style lang="scss" scoped>
.header{
    width: 100%;
    display: flex;
    background-color: var(--header-background-color);

    &__inner{
        padding: 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
}
.navigation ul{
    display: flex;
    list-style-type: none;

    & li{
    margin: 0 10px;
    text-transform: uppercase;

        & a{
        color: var(--header-text-color);
        text-decoration: none;

            &:hover{
                color: var(--header-text-after-color);
            }
        }
    }
}
</style>