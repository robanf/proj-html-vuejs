<template>
  <div>
      <div class="container">
        <div class="row">
          <div class="col-8">
            <img class="my-img-cat" src="@/img/cat_1-1540x750.jpg" alt="">
            <div><strong>Softwere Developer</strong></div>
          </div>
          <div class="col-4 my-img-cat-second">
            <div class="mb-3">
              <img src="@/img/cat_2-370x155.jpg" alt="">
              <div><strong>Art</strong></div>
            </div>
            <div>
              <img src="@/img/cat_3-370x155.jpg" alt="">
              <div><strong>Material Design</strong></div>
            </div>
          </div>
        </div>
        <div class="row my-4 my-img-cat-terzo">
            <div class="col-4">
              <img src="@/img/cat_4-370x155.jpg" alt="">
              <div><strong>Exercize</strong></div>
            </div>
            <div class="col-4">
              <img src="@/img/cat_5-370x155.jpg" alt="">
              <div><strong>Music</strong></div>
            </div>
            <div class="col-4">
              <img src="@/img/cat_6-370x155.jpg" alt="">
              <div><strong>Photography</strong></div>
            </div>
        </div>
      </div>

      <div class="container-fluid">
        <div class="row">
          <div class="col-6">
            <h2>scritta prima col</h2>
          </div>
          <div class="col-6"> immagine col due</div>
        </div>
      </div>

      <div class="container-fluid my-5">
        <div class="row">
          <div class="col">
            <h5>categoria</h5>
            <ul>
              <li class="d-inline-block mx-2">categoria</li>
              <li class="d-inline-block mx-2">categoria</li>
              <li class="d-inline-block mx-2">categoria</li>
              <li class="d-inline-block mx-2">categoria</li>
              <li class="d-inline-block mx-2">categoria</li>
              <li class="d-inline-block mx-2">categoria</li>
              <li class="d-inline-block mx-2">categoria</li>
            </ul>

          </div>

          <div class="row">
            <div class="col-2">my oggetti</div>
          </div>

        </div>
      </div>

      <div class="container-fluid my-5">
        <div class="row">
          <h3>scritte centrale</h3>
          <div>scritta sotto</div>
        </div>
        <div class="row">
          <div class="col-3">contatori</div>
          <div class="col-3">contatori</div>
          <div class="col-3">contatori</div>
          <div class="col-3">contatori</div>
        </div>
      </div>

      <div class="container-fluid my-5">
        <div class="row">
          <div class="col-7">iscriviti</div>
          <div class="col-5">barra per farlo</div>
        </div>
      </div>

      <div class="container-fluid my-5">
        <div class="row">       
          <h3>slider</h3>
        </div>
        <div class="row">
          zona dove andra lo slider
        </div>
      </div>

      <div class="container">
        <div class="row">
          <div class="col-6">roba gemella</div>
          <div class="col-6">roba gemella</div>
        </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  .my-img-cat{
    width: 100%;
  }

  .my-img-cat-second{
    div{
      height: 50%;
      width: 100%;

      img{
        height: 82%;
        width: 89%;
      }

    }
  }

  .my-img-cat-terzo{
      div{
      height: 100%;
      width: calc(98%/3);

      img{
        height: 82%;
        width: 95%;
      }

    }
  }
</style>