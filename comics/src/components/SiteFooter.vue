<template>
    <footer class="site_footer">
        <section id="footer">
            <div class="container">
                <div class="row">
                    <div class="col d-flex p_2">
                        <div class="col">
                            <h4>dc comics</h4>
                            <ul class="mb_1">
                                <li>
                                    <a href="#">Characters</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Movies</a>
                                </li>
                                <li>
                                    <a href="#">Tv</a>
                                </li>
                                <li>
                                    <a href="#">Games</a>
                                </li>
                                <li>
                                    <a href="#">Videos</a>
                                </li>
                                <li>
                                    <a href="#">News</a>
                                </li>
                            </ul>
                            <!-- /DC COMICS -->
                            <h4>shop</h4>
                            <ul>
                                <li>
                                    <a href="#">Shop DC</a>
                                </li>
                                <li>
                                    <a href="#">Shop DC Collectibles</a>
                                </li>
                            </ul>
                            <!-- /SHOP -->
                        </div>
                        <div class="col">
                            <h4>dc</h4>
                            <ul>
                                <li>
                                    <a href="#">Terms Of Use</a>
                                </li>
                                <li>
                                    <a href="#">Privacy policy (new)</a>
                                </li>
                                <li>
                                    <a href="#">Advertising</a>
                                </li>
                                <li>
                                    <a href="#">Subscriptions</a>
                                </li>
                                <li>
                                    <a href="#">Talent Workshops</a>
                                </li>
                                <li>
                                    <a href="#">CPSC Certificates</a>
                                </li>
                                <li>
                                    <a href="#">Ratings</a>
                                </li>
                                <li>
                                    <a href="#">Shop Help</a>
                                </li>
                                <li>
                                    <a href="#">Contact Us</a>
                               </li>
                            </ul>
                            <!-- /DC COMICS -->
                        </div>
                        <div class="col">
                            <h4>Sites</h4>
                            <ul>
                                <li>
                                    <a href="#">DC</a>
                                </li>
                                <li>
                                    <a href="#">MAD Magazine</a>
                                </li>
                                <li>
                                    <a href="#">DC Kids</a>
                                </li>
                                <li>
                                    <a href="#">DC Universe</a>
                                </li>
                                <li>
                                    <a href="#">DC Power Visa</a>
                                </li>
                            </ul>
                            <!-- /SITES -->
                        </div>
                    </div>
                    <!-- /.col sx -->
                    <div class="col">
                        <img src="../assets/img/dc-logo-bg.png" alt="logo dc">
                    </div>
                    <!-- /.col dx -->
                </div>
            </div>
        </section>
        <!-- /#footer -->
        <section id="NavBar">
            <div class="row">
                <div class="col">
                    <div class="btn">
                        <a href="#">sing-up now!</a>
                    </div>
                </div>
                <!-- /.col sx -->
                <div class="col d-flex align-items-center">
                    <h4>follow us</h4>
                    <div class="icons">
                        <img src="@/assets/img/footer-facebook.png" alt="logo facebook">
                        <img src="@/assets/img/footer-twitter.png" alt="logo twitter">
                        <img src="@/assets/img/footer-youtube.png" alt="logo youtube">
                        <img src="@/assets/img/footer-pinterest.png" alt="logo pinterest">
                        <img src="@/assets/img/footer-periscope.png" alt="logo periscope">
                    </div>
                </div>
                <!-- /.col dx -->
            </div>
        </section>
        <!-- /#NavBar -->
    </footer>
</template>



<style lang="scss" scoped>
@import '../assets/sass/variables.scss';

//FOOTER
#footer{
    background-image: url('../assets/img/footer-bg.jpg');
    height: 400px;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}
.row{
    justify-content: space-around;
}
.col{
    .col{
        margin: 10px;
        h4{
            color: white;
            text-transform: uppercase;
        }
        li{
            list-style-type: none;
            margin-bottom: 0.1rem;
                a{
                    text-decoration: none;
                    color: grey;
                }
        }
    }
}

.col{
    img{
        width: 600px;
        margin-top: -120px;
    }
}

#NavBar{
    height: 100px;
    background-color: $Bg-Tertiary;
    position: relative;
    z-index: 1;
    display: flex;
        .row{
            justify-content: space-around;
            align-items: center;
            width: 100%;
                .col{
                    .btn{
                        a{
                            padding: 10px;
                            text-transform: uppercase;
                            color: white;
                            font-weight: 600;
                            border: 1px solid $Bg-Primary;
                        }
                    }
                }
                .col{
                    h4{
                        text-transform: uppercase;
                        font-weight: 600;
                        color: $Bg-Primary;
                    }
                }
        }
}

.icons img{
    width: 30px;
    margin-top: 3px;
    padding: 3px;
}

</style>