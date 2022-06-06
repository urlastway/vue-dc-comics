<template>
    <main>
        <div class="container">
            <div class="container__content">
                <p>Content goes here</p>
            </div>
        </div>
    </main>
</template>



<script>
export default{
    name: 'BaseMain',

}


</script>

<style lang="scss" scoped>
main{
    background-color: var(--main-background-color);
}
.container__content{
    color:var(--main-textcontent-color);
    & p{
        padding: 50px 0;
        font-size: 50px;
    }
}
</style>