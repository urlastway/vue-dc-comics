<template>
    <main>
        <div class="container">
            <div class="main___content">
                <div class="main__content__current__serias">
                    <p>CURRENT SERIAS</p>
                </div>
                <div class="comics__list">
                    <div class="comics" v-for="i in 12" :key="i">
                        <div class="comics__img">
                            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX">
                        </div>
                        <h3 class="comics__name">Action Comics</h3>
                    </div>

                </div>
                
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
    background-image: url(../assets/img/jumbotron.jpg);
    background-repeat: no-repeat;
    background-size: 100% 400px;
    background-color: #1c1c1c;
}
    
.main___content{
    padding-top: 370px;
    padding-bottom: 80px;
}
.main__content__current__serias {

    width: 220px;
    padding: 20px;
    background-color: var(--footer-first-background-color);

    p {

    font-size: 20px;
    color: var(--footer-primary-text-color);
    font-weight: 700;
}

}

.comics__list{
    display: flex;
    flex-wrap: wrap;
    padding: 30px 0;
}
.comics{
    width: calc(100% / 6);
    display: flex;
    flex-direction: column;
    justify-content: center;

    &__name{
        color: var(--footer-primary-text-color);
        text-transform: uppercase;
        font-weight: 300;
        font-size: 14px;
        margin: 10px 0;
    }
    &__img img{
        width: 200px;
        height: 200px;
    }
}
</style>