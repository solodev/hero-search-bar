# hero-search-bar
Search is becoming increasingly important as sites add more and more content. Depending on your industry, it may be that you want users to search for things first rather than navigate throughout a website. Nothing reinforces that action more than adding a search bar to your primary hero section.

## Tutorial
For detailed instruction's, view Solodev's [How to Add a Search Bar to Your Hero Section](https://www.solodev.com/blog/web-design/how-to-add-a-search-bar-to-your-hero-section.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/a153Lutm/).

## HTML
The tutorial contains the following basic HTML markup.

```
  <nav class="navbar h-navbar p-0" role="navigation">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-xl-3 col-lg-2 col-sm-4 col-5">
          <a href="/">
            <img alt="LunarXP Logo" class="img-fluid py-3" src="https://raw.githubusercontent.com/solodev/hero-search-bar/master/images/logo.png" aria-role="logo">
          </a>
        </div>
        <div class="col-xl-9 col-lg-10 col-sm-8 col-7">
          <ul class="navbar-nav flex-row justify-content-end flex-wrap align-items-center mr-lg-4 mr-xl-0">
            <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
              <a class="d-block w-100 h-100 text-white py-4 position-relative top-link" href="#"><strong>About</strong></a>
            </li>
            <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
              <a class="d-block w-100 h-100 text-white py-4 position-relative top-link" href="#"><strong>Locations</strong></a>
            </li>
            <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
              <a class="d-block w-100 h-100 text-white py-4 position-relative top-link" href="#"><strong>Products</strong></a>

            </li>
            <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
              <a class="d-block w-100 h-100 text-white py-4 position-relative top-link" href="#"><strong>Shop</strong></a>
            </li>
            <li class="nav-item px-3 text-uppercase my-3 my-lg-0 mr-5 mr-lg-4 mr-xl-5 d-none d-lg-flex">
              <a class="d-block w-100 h-100 text-white py-4 position-relative top-link" href="#"><strong>Contact</strong></a>
            </li>
          </ul>
          <button id="sidenav-open-btn" class="menu-hamburger position-absolute pointer p-0">
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
        </div>
      </div>
    </div>
  </nav>

  <section class="hero hero--video">
    <div class="container">
      <div class="col-12">
        <div class="search">
          <form>
            <input class="input" type="text" name="s" placeholder="How may we help you?">
            <button type="submit"><i class="fa fa-search"></i></button>
          </form>
        </div>
      </div>
    </div><!-- .container-->
    <video class="d-lg-block" autoplay loop muted>
      <source src="https://raw.githubusercontent.com/solodev/hero-search-bar/master/images/hero-video.mp4" type="video/mp4">
    </video>
  </section><!-- .hero-->
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
```