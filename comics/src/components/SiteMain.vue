<template>
    <main id="project_core">
        <section id="jumbotron"></section>
        <!-- /#jumbotron -->
        <section id="core" class="debug">
            <div class="container">
                <div class="row">
                    <div class="col-2 p_2" v-for="(card, index) in cards" :key="index">
                        <div class="card">
                            <img :src="card.thumb" alt="card.series">
                            <h6 class="text-light">{{card.series}}</h6>
                        </div>
                    </div>
                    <div class="col-12">
                        <div class="btn text-light">
                            <a href="#">load more</a>
                        </div>
                    </div>
                </div>
                <!-- /.row -->
            </div>
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

<script>

export default ({
    data() {
        return {
            cards: [
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                }
            ]
        }
    },
})
</script>


<style lang="scss" scoped>
//@import '../assets/sass/variables.scss';
@import '../assets/sass/style.scss';

//DEBUG
.debug{
    background-color: black;
}

//MAIN
#jumbotron{
    background-image: url('../assets/img/jumbotron.jpg');
    height: 400px;
    background-position: initial;
    background-size: cover;
    background-repeat: no-repeat;
}

#core{
    .container{
        padding: 5rem;
    }
}
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

.col-12{
    display: flex;
    justify-content: center;
    margin-top: 50px;
    .btn{
        @include btn;
        a{
            color: white;
            text-decoration: none;
        }
    }
}

</style>