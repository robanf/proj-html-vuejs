<template>
  <div class="header">
      <div class="container-fluid">
        <div class="row d-flex justify-content-between">
          <div class="col-4 my-3 dropdown">
              <div>Inglese</div>
              <ul class="my-lenguage ">
                  <li> Inglese</li>
                  <li>Italiano</li>
                  <li>Spagnolo</li>
              </ul>
          </div>
          <div class="col-8 my-3">
              <nav class="first-nav d-flex justify-content-end">
                  <div>
                    <ul>
                      <li>Courses</li>
                      <li class="position-relative">Zoom 
                        <div class="box-red rounded-top rounded-end">Hot</div>
                      </li>
                      <li class="dropdown">Pages
                        <ul class="my-nav-drop">
                          <li>link</li>
                          <li>link</li>
                          <li>link</li>
                          <li>link</li>
                          <li>link</li>
                        </ul>
                      </li>
                      <li>Bundles</li>
                      <li class="dropdown">Course Formats
                        <ul class="my-nav-drop">
                          <li>link</li>
                          <li>link</li>
                          <li>link</li>
                          <li>link</li>
                          <li>link</li>
                        </ul>
                      </li>
                      <li class="position-relative">Add Course
                        <div class="box-red rounded-top rounded-end">Hot</div>
                      </li>
                      <li class="dropdown">Demos
                        <ul class="my-nav-drop">
                          <li>link</li>
                          <li>link</li>
                          <li>link</li>
                          <li>link</li>
                          <li>link</li>
                        </ul>
                      </li>
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
          <div class="col-2 d-flex  align-items-center">
            <img src="/img/MasterStudy_logo.svg" alt="">
          </div>
          <div class="col-4 d-flex  align-items-center">
            <div class="dropdown d-inline-block mx-3">
                    <div><i class="fas fa-bars"></i><strong>CATEGORY</strong></div>
                    <ul class="my-category ">
                      <li>ART</li>
                      <li>EXERCISE</li>
                      <li>MATERIAL DESIGN</li>
                      <li>MUSIC</li>
                      <li>PHOTOGRAPY</li>
                      <li>SOFTWARE DEVELEPMENT</li>
                    </ul>
            </div>
            <div class="d-inline-block">
              <input type="text" class="serch-text border-0" placeholder="Search courses">
              <div class="btn btn-primary"><i class="fas fa-search"></i></div>
            </div>
          </div>
          <div class="col-3 d-flex align-items-center">
              <a href="#"><i class="fas fa-bullhorn"></i>Became a istructor</a>
              <a class="mx-4" href="#"><i class="fas fa-briefcase"></i>For enterprise</a>
          </div>
          <div class="col-3">
            <a href="#"><i class="far fa-user"></i>Log in</a>
            <div class="btn btn-primary rounded-pill mx-5 sign-btn"><strong>SIGN UP </strong></div>
            <a href="#" class="fs-3"><i class="far fa-bookmark"></i></a>
          </div>
          <nav>
              
          </nav>
        </div>
        </div>
        <div class="container my-cont-jumbo">
            <div class="row align-items-center ">
              <div class="col-6 jumbo">
                  <h2>Start Investing in You</h2>
                  <div class="jumbo-text">With over 1200 courses in 18 subjects, you're guaranteed to find something that's right for you.</div>
                  <div class="btn btn-primary rounded-pill my-btn">Join for free </div>
              </div>
              <div class="col-6"><img src="/img/base.png" alt=""></div>
          </div>
        </div>
        <div class="container ">
            <div class="row mt-5 justify-content-evenly">
              <div class="col-4 mx-3 box-test"> 
                  <div class="icon"><i class="fas fa-globe-europe"></i></div>
                  <div> <strong>Worldwide Recognize</strong></div>
                  <div>Our online course certificates can be used around the world and also in most popular universities and companies.</div>
              </div>
              <div class="col-4 mx-3 box-test">
                <div class="icon"><i class="fas fa-tv"></i></div>
                <div> <strong>Mostly Online Learning (sd)</strong></div>
                <div>Masterstudy online certificates can be obtained in a range of specialized areas and typically take about a year to complete.</div>
              </div>
              <div class="col-4 mx-3 box-test">
                  <div class="icon"><i class="far fa-calendar-alt"></i></div>
                  <div> <strong>Graduate in as little as 1 Year</strong></div>
                  <div>Online post-graduate certificates are a popular way to develop your professional qualifications of Masterstudy</div>
              </div>
            </div>
        </div>

      </div>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  .header{
    background-color: white;
  }
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

  .my-cont-jumbo{
    margin-top:85px ;
  }
  .box-test{
    height: 215px;
    width: 379px;
    background-color: #F2F6FB;
    padding: 10px 20px;
      .icon{
        font-size: 50px;
        color:#316FCE;
      }
  }
  .jumbo{
      h2{
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
  .serch-text{
    padding: 6px 30px;
    background-color: #F0F2F5;
  }

  .sign-btn{
    padding: 10px 25px;
  }

  .dropdown{
      color: #767676;
      position: relative;
      padding-bottom:10px ;
    .my-category{
      margin-top:10px;
       white-space: nowrap;
        display: none;
        color: #000;
        box-shadow: 10px 10px 5px grey;
        list-style: none;
        position: absolute;
        li{
          margin: 5px 0px;
        }
    }
    .my-lenguage{
      margin-top:10px;
       white-space: nowrap;
        display: none;
        color: #000;
        background-color:  lightgray;
        list-style: none;
        position: absolute;
        li{
          margin: 5px 0px;
        }
    }
    .my-nav-drop{
      text-align: center;
      /* margin-top:7px; */
        width: 100px;
        padding-right: 20px;
        display: none;
        color: #000;
        box-shadow: 10px 10px 5px grey;
        border:1px solid gray;
        border-top:4px solid lime ;
        background-color: white;
        list-style: none;
        position: absolute;
        li{
          margin: 5px 0px;
          text-align: center;
          &:hover{
            color: lime;
          }
        }
    }

    &:hover{
       .my-category , .my-lenguage , .my-nav-drop{
        display: block;
        li{
          display: block;
        }
        
        }
    }
  }

  .box-red{
    font-size: 10px;
    position: absolute;
    color: white;
    top: -14px;
    right: -13px;
    padding: 1px 3px;
    border: 1px solid rgb(211, 28, 28);
    background-color: rgb(211, 28, 28);
  }
</style>