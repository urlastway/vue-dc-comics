<template>
    <header class="header">
        <div class="container">
            <div class="header__logo">
                <img src="../assets/img/dc-logo.png">
            </div>
            <nav class="navigation">
                
            </nav>
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
    justify-content: space-between;
    background-color: var(--header-background-color);
}
.header__logo{
    padding: 20px;
}
</style>