<template>
    <footer>
        <div class="footer__up">
            <div class="container">
                <div class="footer__up__content">
                    <div class="col-5">
                        <div class="footer__shop__img">
                            <img src="../assets/img/buy-comics-digital-comics.png">
                        </div>
                        <div class="footer__shop__text">
                            <p>digital comics</p>
                        </div>
                    </div>
                    <div class="col-5">
                        <div class="footer__shop__img">
                            <img src="../assets/img/buy-comics-merchandise.png">
                        </div>
                        <div class="footer__shop__text">
                            <p>ds nerchandise</p>
                        </div>
                    </div>
                    <div class="col-5">
                        <div class="footer__shop__img">
                            <img src="../assets/img/buy-comics-subscriptions.png">
                        </div>
                        <div class="footer__shop__text">
                            <p>substiptions</p>
                        </div>
                    </div>
                    <div class="col-5">
                        <div class="footer__shop__img">
                            <img src="../assets/img/buy-comics-shop-locator.png">
                        </div>
                        <div class="footer__shop__text">
                            <p>comic shop locator</p>
                        </div>
                    </div>
                    <div class="col-5">
                        <div class="footer__shop__img">
                            <img src="../assets/img/buy-comics-shop-locator.png">
                        </div>
                        <div class="footer__shop__text">
                            <p>dc power visa</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer__midle">

        </div>
        <div class="footer__down">

        </div>
    </footer>
</template>



<script>
export default{
    name: 'BaseFooter',

}


</script>

<style lang="scss" scoped>
.footer__up{
    background-color: var(--footer-first-background-color);
    padding: 50px;

    &__content{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
}
.col-5{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.footer__shop{
     &__text{
         color: var(--footer-primary-text-color);
         padding: 20px;
         text-transform: uppercase;
         font-size: 16px;
     }
     &__img img{
         max-width: 60px;
         max-height: 60px;
     }
}
</style>