<template>
  <div>
      <div class="container">
        <div class="row">
          <div class="col-8">
            <img class="my-img-cat" src="/img/cat_1-1540x750.jpg" alt="">
            <div><strong>Softwere Developer</strong></div>
          </div>
          <div class="col-4 my-img-cat-second">
            <div class="mb-3">
              <img src="/img/cat_2-370x155.jpg" alt="">
              <div><strong>Art</strong></div>
            </div>
            <div>
              <img src="/img/cat_3-370x155.jpg" alt="">
              <div><strong>Material Design</strong></div>
            </div>
          </div>
        </div>
        <div class="row my-4 my-img-cat-terzo">
            <div class="col-4">
              <img src="/img/cat_4-370x155.jpg" alt="">
              <div><strong>Exercize</strong></div>
            </div>
            <div class="col-4">
              <img src="/img/cat_5-370x155.jpg" alt="">
              <div><strong>Music</strong></div>
            </div>
            <div class="col-4">
              <img src="/img/cat_6-370x155.jpg" alt="">
              <div><strong>Photography</strong></div>
            </div>
        </div>
      </div>

      <div class="container-fluid second-jumbo d-flex align-items-center">
        <div class="row">
          <div class="col-6 ps-5">
            <h2>Limitless learning, more possibilities</h2>
            <div class="jumbo-text my-4">Online courses open the opportunity for learning to almost anyone, regardless of their scheduling commitments.</div>
            <div class="btn btn-primary rounded-pill my-btn"> Read More</div>
          </div>
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
            <div v-for="(element,index) in array" :key="index" class="col-2 ">
              <div class="card" style="height:20rem ;width: 15rem;">
                <img :src="'/img/'+element.img" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">{{element.type}}</h5>
                  <p class="card-text"><strong>{{element.name}}</strong></p>
                  <hr>
                  <p class="card-text">
                    <span v-if="element.vote!=0"> <span v-for="(e,i) in element.vote" :key="i"><img src="/img/starfull.svg" alt=""></span><span v-for="(e,i) in 5-element.vote" :key="i"><img src="/img/staremptyl.svg" alt=""></span></span>    
                    <span v-else><strong>{{element.time}} </strong></span>
                  <strong> ${{element.cost}}</strong></p>
                </div>
              </div>
            </div>
            <div v-for="(element,index) in array" :key="index" class="col-2 ">
              <div class="card" style="height:20rem ;width: 15rem;">
                <img :src="'/img/'+element.img" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">{{element.type}}</h5>
                  <p class="card-text"><strong>{{element.name}}</strong></p>
                  <hr>
                  <p class="card-text">
                    <span v-if="element.vote!=0"> <span v-for="(e,i) in element.vote" :key="i"><img src="/img/starfull.svg" alt=""></span><span v-for="(e,i) in 5-element.vote" :key="i"><img src="/img/staremptyl.svg" alt=""></span></span>    
                    <span v-else><strong>{{element.time}} </strong></span>
                  <strong> ${{element.cost}}</strong></p>
                </div>
              </div>
            </div>
            <div v-for="(element,index) in array" :key="index" class="col-2 ">
              <div class="card" style="height:20rem ;width: 15rem;">
                <img :src="'/img/'+element.img" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">{{element.type}}</h5>
                  <p class="card-text"><strong>{{element.name}}</strong></p>
                  <hr>
                  <p class="card-text">
                    <span v-if="element.vote!=0"> <span v-for="(e,i) in element.vote" :key="i"><img src="/img/starfull.svg" alt=""></span><span v-for="(e,i) in 5-element.vote" :key="i"><img src="/img/staremptyl.svg" alt=""></span></span>    
                    <span v-else><strong>{{element.time}} </strong></span>
                  <strong> ${{element.cost}}</strong></p>
                </div>
              </div>
            </div>
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
  props:{
    array:Array
  }
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
        width: 95%;
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

  .second-jumbo{
    height: 83vh;
    background-image: url("/img/Untitled-1-1-1-1-1.png");
      h2{
        padding-top: 30px;
        font-size: 67px;
      }
      .jumbo-text{
        font-size: 25px;
        margin: 15px 0px;
      }
      .my-btn{
        font-size: 25px;
        padding: 10px 20px;
      }
  }
</style>