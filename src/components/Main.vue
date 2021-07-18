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
          <div class="col text-center filtro">
            <h2>Recent courses</h2>
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
          </div>

        </div>
      </div>

      <div class="container-fluid mt-5 my-numbers">
        <div class="row">
          <div class="col text-center filtro">
            <h2>We are Proud</h2>
            <div>Certificate courses are instructed by highly educated and qualified instructors who hold doctoral and master’s level degrees.</div>

          </div>
        </div>
        <div class="row my-5 my-data-num">
          <div class="col-3 text-center">
               <h2>2000</h2>
               <div>STUDENTS</div>
            </div>
          <div class="col-3 text-center border-start border-3">
              <h2>950</h2>
              <div>COURSES</div>
            </div>
          <div class="col-3 text-center border-start border-end border-3">
               <h2>1600</h2>
               <div>HOURS VIDEO</div>
            </div>
          <div class="col-3 text-center">
                <h2>150</h2> 
                <div>COUNTRIES REACHED</div>
            </div>
        </div>
      </div>

      <div class="container-fluid">
        <div class="row my-iscrizione align-items-center">
          <div class="col-7">
                <h3>Subscribe our newsletter</h3>
                <div>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words</div>
            </div>
          <div class="col-5">
            <h5>YOUR E-MAIL ADDRESS</h5>
            <input type="text" class="sub-text" placeholder="Inserisci la tua email">
            <div class="btn btn-primary">Subscribe</div>
          </div>
        </div>
      </div>

      <div class="container-fluid mb-5">
        <div class="row">       
          <h3>slider</h3>
        </div>
        <div class="row flex-nowrap overflow-hidden my-slide" >
            <div v-for="(element,index) in array" :key="'A'+index" class="col-2 " :style="'transform: translateX('+muovi+'px);'">
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
        <div class="row d-flex justify-content-center my-4">
            <div class="col d-flex justify-content-center">
              <div class="p-3 my-arrow mx-3" id="right" @click="left"><i class="fas fa-arrow-left"></i></div>
              <div class="p-3 my-arrow mx-3" @click="right"><i class="fas fa-arrow-right"></i></div>
            </div>
        </div>
        <div class="row">
              <div class="box" :style="'margin-left:'+muovi+'px;'"></div>
        </div>
      </div>

      <div class="container">
        <div class="row">
          <div class="col-6 my-twin d-flex align-items-center mx-4">
            <img src="/img/image_box_1-221x231.png" alt="">
            <div class="ms-3">
              <h3><strong>Become an Instructor</strong></h3>
              <div class="my-2">Teach what you love. Masterstudy gives you the tools to create a course.</div>
              <div class="btn btn-primary rounded-pill my-btn">START TECHING</div>
            </div>
          </div>
          <div class="col-6 my-twin d-flex align-items-center mx-4">
            <img src="/img/image_box_2-234x231.png" alt="">
            <div class="ms-3">
              <h3><strong>Setup For Business</strong></h3>
              <div class="my-2">Get unlimited access to 2,500 of Udemy’s top courses for your team.</div>
              <div class="btn btn-primary rounded-pill my-btn">DOING BUISNESS</div>
            </div>
          </div>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  props:{
    array:Array
  },
  data(){
    return{
      overarray:[],
      count:7,
      muovi:0,
    }
  },
  methods:{
    nextitem(){
      console.log(this.count);
      this.count+=1
    },
    right(){
      if(this.muovi>-1518){
        this.muovi-=253;

      }
        console.log(this.muovi);
        /* -1771 numero limite */
    },
    left(){
      if(this.muovi!=0){
        this.muovi+=253;

      }
    }
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
        width: 95%
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

  .filtro{
    h2{
      font-size: 50px;
    }
    ul{
      margin: 20px 0px;

    }
  }

  .my-numbers{
    height: 80vh;
    background-color: #F0F4FA;
    background-image: url("/img/we_proud.png");
    background-size:cover ;
    background-position: center;
    .my-data-num{
      padding: 30px;
      padding-bottom: 50px;
      h2{
        font-size: 70px;
      }
      div{
        font-size: 25px;
      }
    }

  }

  .my-iscrizione{
    height: 300px;
    background-color: #4ED7A8;
    color: white;
      .sub-text{
        padding: 5px 40px;
      }
  }

  .my-twin{
    height: 400px;
    width: 600px;
    border: 1px solid black;
    padding: 60px 40px;
  }

  .my-arrow{
    background-color: wheat;
     animation-name:slidein;
     animation-duration: 3s;
  }

  

  .my-slide{
     animation-duration: 3s;
      animation-name: slidein;

  }

  .box{
    height: 50px;
    width: 50px;
    background-color: crimson;
  }


      
.slide-enter-enter-active {
  transition: slidein .3s infinite;
}

.slide-fade-enter
/* .slide-fade-leave-active below version 2.1.8 */ {
  transform: translateX(100px);
}

    @keyframes slidein {
              
              from {
              margin-left: 100%;
            }

            to {
              margin-left: 0%;
            }
          }



</style>