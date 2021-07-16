<template>
  <div>
      <div class="container-fluid">
        <div class="row d-flex justify-content-between">
          <div class="col-4">
              <div>dropdown lingue</div>
          </div>
          <div class="col-8">
              <nav class="first-nav d-flex justify-content-end">
                  <div>
                    <ul>
                      <li>menu 1nav</li>
                      <li>menu 1nav</li>
                      <li>menu 1nav</li>
                      <li>menu 1nav</li>
                      <li>menu 1nav</li>
                      <li>menu 1nav</li>
                      <li>menu 1nav</li>
                    </ul>
                  </div>
                  <div class="icone">
                    <i class="fab fa-twitter"></i>
                    <i class="fab fa-instagram"></i>
                    <i class="fab fa-behance"></i>
                    <i class="fas fa-basketball-ball"></i>
                    <i class="fab fa-flickr"></i>
                    <i class="fab fa-git"></i>
                    <i class="fab fa-linkedin"></i>
                    <i class="fab fa-pinterest"></i>
                  </div>
              </nav>
          </div>
          <hr>
        </div>
        <div class="row mb-5">
          <div class="col-3">logo</div>
          <div class="col-3"> dropdown e serchbar</div>
          <div class="col-3"> link inutili</div>
          <div class="col-3"> registrazione</div>
          <nav>
              
          </nav>
        </div>
        </div>
        <div class="container">
            <div class="row mt-5">
              <div class="col-6">
                  <h2>il mio jumbotron</h2>
              </div>
              <div class="col-6"> la mia img del jumbo  </div>
          </div>
        </div>
        <div class="container mb-5">
            <div class="row mt-5 justify-content-evenly">
              <div class="col-4 mx-3 box-test"></div>
              <div class="col-4 mx-3 box-test"></div>
              <div class="col-4 mx-3 box-test"></div>
            </div>
        </div>

      </div>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  .first-nav{
    *{
      margin: 0 7px;
      color: #777777;
    }
    li{
      display: inline-block;
      font-size: 14px;

    }
  }
  .box-test{
    height: 200px;
    width: 350px;
    background-color: gray;
  }
</style>