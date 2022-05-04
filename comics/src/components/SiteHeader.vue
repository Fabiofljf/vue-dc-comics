<template>
  <header id="menu" class="debug">
      <div class="container">
        <div class="row">
          <div class="col">
            <img src="../assets/img/dc-logo.png" alt="logo comics">
          </div>
          <!-- /.col sx -->
          <div class="col navbar">
              <ul class="d-flex">
                <li v-for="({href, title}, index) in lists" :key="index">
                  <a :href="href">{{title}}</a>
                </li>
              </ul>
          </div>
          <!-- /.col dx -->
        </div>
      </div>
      <!-- /#menu -->
  </header>
</template>

<script>

export default({
  data() {
    return {
      lists:[
        {
        id: 1,
        href: '#',
        title: 'characters'
        },
        {
        id: 2,
        href: '#',
        title: 'comics'
        },
        {
        id: 3,
        href: '#',
        title: 'movies'
        },
        {
        id: 4,
        href: '#',
        title: 'tv'
        },
        {
        id: 5,
        href: '#',
        title: 'games'
        },
        {
        id: 6,
        href: '#',
        title: 'collectibles'
        },
        {
        id: 7,
        href: '#',
        title: 'videos'
        },
        {
        id: 8,
        href: '#',
        title: 'fans'
        },
        {
        id: 9,
        href: '#',
        title: 'news'
        },
        {
        id: 10,
        href: '#',
        title: 'shop'
        },
      ]
    }
    
  },
})
</script>


<style lang="scss" scoped>
@import '../assets/sass/variables.scss';

//FOOTER
#menu{
  height: 120px;
}
.row{
  justify-content: space-around;
}

.col{
  display: flex;
  align-self: center;
  justify-content: center;
}

img{
  width: 75%;
}

li{
  list-style-type: none;
  text-transform: uppercase;
  padding-left: 0.5rem;
  padding-right: 0.5rem;
    a{
      color: $C-NavBar;
      font-weight: 600;
      text-decoration: none;
        &:hover{
        color: $Bg-Primary;
        border-bottom: 10px solid $Bg-Primary;
        padding-bottom: 46px;
        }
    }
}
</style>