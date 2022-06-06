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
            <div class="container">
                <div class="footer__midle__content">
                    <div class="footer__midle__content__left">
                        <div class="col-3">
                            <h2 class="footer__midle__content__left__title">
                                dc comics
                            </h2>
                            <p class="footer__midle__content__left__subtitle">
                                <ul>
                                    <li><a href="#">Characters</a></li>
                                    <li><a href="#">Comics</a></li>
                                    <li><a href="#">movies</a></li>
                                    <li><a href="#">tv</a></li>
                                    <li><a href="#">games</a></li>
                                    <li><a href="#">colectiblers</a></li>
                                    <li><a href="#">videos</a></li>
                                    <li><a href=#>news</a></li>
                                </ul>
                            </p>
                            <h2 class="footer__midle__content__left__title">
                                shop dc
                            </h2>
                            <p class="footer__midle__content__left__subtitle">
                                <ul>
                                    <li><a href="#">Shop DC</a></li>
                                    <li><a href="#">shop DC Collectibles</a></li>
                                </ul>
                            </p>
                        </div>
                        <div class="col-3">
                            <h2 class="footer__midle__content__left__title">
                                dc
                            </h2>
                            <p class="footer__midle__content__left__subtitle">
                                <ul>
                                    <li><a href="#">Characters</a></li>
                                    <li><a href="#">Comics</a></li>
                                    <li><a href="#">movies</a></li>
                                    <li><a href="#">tv</a></li>
                                    <li><a href="#">games</a></li>
                                    <li><a href="#">colectiblers</a></li>
                                    <li><a href="#">videos</a></li>
                                    <li><a href=#>news</a></li>
                                    <li><a href="#">tv</a></li>
                                    <li><a href="#">games</a></li>
                                    <li><a href="#">colectiblers</a></li>
                                    <li><a href="#">videos</a></li>
                                </ul>
                            </p>
                        </div>
                        <div class="col-3">
                            <h2 class="footer__midle__content__left__title">
                                sites
                            </h2>
                            <p class="footer__midle__content__left__subtitle">
                                <ul>
                                    <li><a href="#">Characters</a></li>
                                    <li><a href="#">Comics</a></li>
                                    <li><a href="#">movies</a></li>
                                    <li><a href="#">tv</a></li>
                                    <li><a href="#">games</a></li>
                                </ul>
                            </p>
                        </div>
                    </div>
                    <div class="footer__midle__content__right">
                        <img src="../assets/img/dc-logo-bg.png">
                    </div>
                </div>
            </div>
        </div>
        <div class="footer__down">
            <div class="container">
                <div class="footer__down__content">
                    <div class="footer__down__left">
                        <p><a href="#">Sing-up now</a></p>
                    </div>
                    <div class="footer__down__right">
                        <p>Folow us</p>
                        <img src="../assets/img/footer-facebook.png">
                        <img src="../assets/img/footer-periscope.png">
                        <img src="../assets/img/footer-pinterest.png">
                        <img src="../assets/img/footer-periscope.png">
                        <img src="../assets/img/footer-pinterest.png">
                    </div>
                </div>
            </div>

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
.col-3{
    padding: 0 30px;
}
.footer__midle{
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;

    padding: 0;

    &__content{
        display: flex;
        justify-content: space-between;

        &__left{
            display: flex;

            &__title{
                text-transform: uppercase;
                color: var(--footer-primary-text-color);
                padding: 30px 0;
            }

            &__subtitle{

                 ul{
                    list-style-type: none;
                }

                 ul li {

                    padding-bottom: 10px;

                    a{

                        color: var(--footer-second-text-color);
                        padding-bottom: 10px;
                        text-decoration: none;
                        
                    }
                }
            }

        }
    }
}
.footer__down__content{
    display: flex;
    padding: 40px;
    align-items: center;
    justify-content: space-between;
}
.footer__down{
    background-color: var(--footer-second-background-color);

    &__left p a{
        text-decoration: none;
        color: #fff;
        text-transform: uppercase;
        font-size: 16px;
        padding: 15px;
        border: solid 2px var(--footer-buttons-color);
    }
    &__right {
        display: flex;

        img{
            margin: 0 10px;
        }

        p{
            text-transform: uppercase;
            color: var(--footer-buttons-color);
            font-size: 26px;
            margin-right: 20px;
        }
    }
}

</style>