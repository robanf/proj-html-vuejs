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
            <div class="row align-items-center mt-5">
              <div class="col-6 jumbo">
                  <h2>Start Investing in You</h2>
                  <div class="jumbo-text">With over 1200 courses in 18 subjects, you're guaranteed to find something that's right for you.</div>
                  <div class="btn btn-primary rounded-pill my-btn">Join for free </div>
              </div>
              <div class="col-6"><img src="/img/base.png" alt=""></div>
          </div>
        </div>
        <div class="container mb-5">
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
</style>