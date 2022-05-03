<template>
    <main id="project_core">
        <section id="core" class="debug">
            <div class="row">
                <div class="col">
                    <h2 class="text-light">Content goes here...</h2>
                </div>
            </div>
            <!-- /.row -->
        </section>
        <!-- /#core -->
        <section id="banner" class="bg-row">
            <div class="row">
                <div class="col">
                    <div class="card">
                        <a href="#">
                            <img src="../assets/img/buy-comics-digital-comics.png" alt="digital comics">
                            <h5>digital comics</h5>
                        </a>
                    </div>
                </div>
                <!-- /.col -->
                <div class="col">
                    <div class="card">
                        <a href="#">
                            <img src="../assets/img/buy-comics-merchandise.png" alt="dc merchandise">
                            <h5>dc merchandise</h5>
                        </a>
                    </div>
                </div>
                <!-- /.col -->
                <div class="col">
                    <div class="card">
                        <a href="#">
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
                            <h5>subscriptions</h5>
                        </a>
                    </div>
                </div>
                <!-- /.col -->
                <div class="col">
                    <div class="card">
                        <a href="#">
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="shop locator">
                            <h5>comics shop locator</h5>
                        </a>
                    </div>
                </div>
                <!-- /.col -->
                <div class="col">
                    <div class="card">
                        <a href="#">
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="dc power visa">
                            <h5>dc power visa</h5>
                        </a>
                    </div>
                </div>
                <!-- /.col -->
            </div>
            <!-- /.row -->
        </section>
        <!-- /#banner -->
    </main>
    <!-- /#project_core -->
</template>

<style lang="scss" scoped>
@import '../assets/sass/variables.scss';

//DEBUG
.debug{
    background-color: black;
    height: 200px;
}

//MAIN
#banner{
    display: flex;
    justify-content: center;
    position: relative;
    z-index: 1;
        .row{
            justify-content: space-around;
            align-items: center;
            width: 70%;
            flex-wrap: nowrap;
        }
        .card{
                a{
                    display: flex;
                    padding: 2rem;
                    color: white;
                    font-size: 14;
                    font-weight: 600;
                }
                img{
                    width: 50px;
                }

                h5{
                text-transform: uppercase;
                padding: 0.4rem;
                align-self: center;
                }
        }
}    

.bg-row{
    background-color: $Bg-Primary;
}

</style>