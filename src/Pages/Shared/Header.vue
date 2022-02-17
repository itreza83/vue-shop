<template>
  <header id="header">
    <div class="header-middle">
      <!--header-middle-->
      <div class="container">
        <div class="row">
          <div class="col-sm-4" style="text-align: left;">
            <div class="logo">
              <a href="index.html">
                <img src="src/assets/images/home/logo.png" alt="Logo" style="text-align: center;">
              </a>
            </div>
          </div>

          <div class="col-sm-8 header-middle-menu">
            <div class="shop-menu pull-right">
              <ul class="nav navbar-nav">
                <li>
                  <a href="login.html">
                    <i class="fa fa-lock"></i> ورود
                  </a>
                </li>
                <li>
                  <a href="register.html">
                    <i class="fa fa-user"></i> ثبت نام
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="header-bottom">
      <!--header-bottom-->
      <div class="container">
        <div class="row">
          <div class="col-sm-9 pull-right">
            <div class="navbar-header">
              <button
                type="button"
                class="navbar-toggle"
                data-toggle="collapse"
                data-target=".navbar-collapse"
              >
                <span class="sr-only">Toggle navigation</span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
              </button>
            </div>
            <div class="mainmenu pull-right">
              <ul class="nav navbar-nav collapse navbar-collapse">
                <li>
                  <router-link to="/" active-class="active" exact>خانه</router-link>
                </li>
                <li class="dropdown">
                  <a href="shop.html">محصولات</a>
                </li>
                <li>
                  <router-link to="/AboutUs" active-class="active">درباره مـا</router-link>
                </li>
                <li>
                  <a href="cart.html">سبد خرید</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--/header-bottom-->
  </header>
</template>
