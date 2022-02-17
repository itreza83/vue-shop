<template>
  <div>
   <section id="slider">
      <!--slider-->
      <div class="container">
        <div class="row">
          <div class="col-sm-12">
            <div id="slider-carousel" class="carousel slide" data-ride="carousel">
              <ol class="carousel-indicators">
                <li data-target="#slider-carousel" data-slide-to="0" class="active"></li>
                <li data-target="#slider-carousel" data-slide-to="1"></li>
              </ol>

              <div class="carousel-inner">
                <div class="item active">
                  <div class="col-sm-6">
                    <h2>ساعت دیواری</h2>
                    <p>یه ساعت دیواری خوشگل برای دیوار خونتون !!!</p>
                  </div>
                  <div class="col-sm-6">
                    <img
                      src="src/assets/images/home/slider-1.jpg"
                      width="484"
                      height="441"
                      class="girl img-responsive"
                      alt
                    >
                  </div>
                </div>

                <div class="item">
                  <div class="col-sm-6">
                    <h2>زود پز</h2>
                    <p>
                      این زودپز 6 لیتری برای 2 تا 4 نفر کافی است و به راحتی و واقعا با یک دست می‌توان در آن را باز کرد. عملکرد
                      زودپز به این صورت است که با تحت فشار دادن مواد داخلش آن را به سرعت و البته با حفظ مواد مغذی می‌پزد به همین
                      دلیل برای اوقاتی که فرصت کافی برای پختن غذا نیست می‌تواند بسیار کمک کننده باشد.
                    </p>
                  </div>
                  <div class="col-sm-6">
                    <img
                      src="src/assets/images/home/slider-2.jpg"
                      width="484"
                      height="441"
                      class="girl img-responsive"
                      alt
                    >
                  </div>
                </div>
              </div>

              <a href="#slider-carousel" class="left control-carousel hidden-xs" data-slide="prev">
                <i class="fa fa-angle-left"></i>
              </a>
              <a href="#slider-carousel" class="right control-carousel hidden-xs" data-slide="next">
                <i class="fa fa-angle-right"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
    </template>