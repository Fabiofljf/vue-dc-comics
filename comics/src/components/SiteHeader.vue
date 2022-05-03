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
                <li>
                  <a href="">characters</a>
                </li>
                <li>
                  <a href="">comics</a>
                </li>
                <li>
                  <a href="">movies</a>
                </li>
                <li>
                  <a href="">tv</a>
                </li>
                <li>
                  <a href="">games</a>
                </li>
                <li>
                  <a href="">collectibles</a>
                </li>
                <li>
                  <a href="">videos</a>
                </li>
                <li>
                  <a href="">fans</a>
                </li>
                <li>
                  <a href="">news</a>
                </li>
                <li>
                  <a href="">shop</a>
                </li>
              </ul>
          </div>
          <!-- /.col dx -->
        </div>
      </div>
      <!-- /#menu -->
  </header>
</template>

<style lang="scss" scoped>
//DEBUG
.debug{
  background-color: lightblue;
}

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
}
</style>