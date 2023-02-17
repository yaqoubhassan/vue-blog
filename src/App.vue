<template>
  <header>
    <a href="#" style="text-decoration: none; color: black">
      <div class="text-center app-brand">
        <h1>P E R S <span style="color: #EFA48D"> O </span>N A</h1>
        <p>PERSONAL BLOGGING TEMPLATE</p>
      </div>
    </a>

    <nav class="navbar navbar-expand-lg" id="nav">
      <div class="container navbar-menu">
        <a class="navbar-brand" href="#" style="flex-grow: 1" id="socials">Navbar</a>
        <a class="navbar-brand" href="#" style="flex-grow: 1" id="mobile-logo">Persona.</a>
        <button class="navbar-toggler custom-toggler" type="button" data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
          aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0 ms-auto menu-items">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="javascript:void(0)">HOME</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:void(0)">FEATURES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:void(0)">LIFESTYLE</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:void(0)">TRAVEL</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:void(0)">MUSIC</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:void(0)">BUY THIS THEME</a>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2 search-input" type="search" placeholder="Search" aria-label="Search">
            <button class="btn search-btn-outline" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
  </header>

  <main>
    <section class="carousel-section">
      <div class="container">
        <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
              aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
              aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
              aria-label="Slide 3"></button>
          </div>
          <div class="carousel-inner content">
            <div class="carousel-item active " data-bs-interval="2000">
              <img
                src="https://img.freepik.com/free-photo/wide-angle-shot-single-tree-growing-clouded-sky-during-sunset-surrounded-by-grass_181624-22807.jpg"
                class="d-block w-100 img-fluid" alt="Nature-Image-1">
              <div class="carousel-caption d-none d-md-block pb-5 mb-5">
                <h5><a href="">Wild Animals Preparing Food For His Own Parents</a></h5>
                <p>DECEMBER 07, 2016</p>
                <button id="carousel-btn">CONTINUE READING</button>
              </div>
            </div>
            <div class="carousel-item content" data-bs-interval="2000">
              <img src="https://cdn.pixabay.com/photo/2014/02/27/16/10/flowers-276014__340.jpg"
                class="d-block w-100 img-fluid" alt="Nature-Image-2">
              <div class="carousel-caption d-none d-md-block pb-5 mb-5">
                <h5><a href="">Wild Animals Preparing Food For His Own Parents</a></h5>
                <p>DECEMBER 07, 2016</p>
                <button id="carousel-btn">CONTINUE READING</button>
              </div>
            </div>
            <div class="carousel-item content" data-bs-interval="2000">
              <img
                src="https://images.unsplash.com/photo-1618588507085-c79565432917?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8YmVhdXRpZnVsJTIwbmF0dXJlfGVufDB8fDB8fA%3D%3D&w=1000&q=80"
                class="d-block w-100 img-fluid" alt="Nature-Image-3">
              <div class="carousel-caption d-none d-md-block pb-5 mb-5">
                <h5><a href="">Wild Animals Preparing Food For His Own Parents</a></h5>
                <p>DECEMBER 07, 2016</p>
                <button id="carousel-btn">CONTINUE READING</button>
              </div>
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </section>
    <section>
      <div class="container text-center">
        <div class="row  g-4 py-5">
          <div class="col-xl-3 col-lg-3 col-md-3">
            <div class="card">
              <div class="bg-image hover-overlay ripple shadow-1-strong" data-mdb-ripple-color="light">
                <img
                  src="https://img.freepik.com/free-photo/wide-angle-shot-single-tree-growing-clouded-sky-during-sunset-surrounded-by-grass_181624-22807.jpg"
                  class="card-img-top" alt="...">
                <a href="#!">
                  <div class="mask" style="background-color: hsl(0, 0%, 98%, 0.2)"></div>
                </a>
              </div>
              <div class="card-body">
                <h5 class="card-title"><a href="#">The Top Handpicked</a></h5>
                <h6 class="card-subtitle my-2 text-muted">SEPTEMBER 16, 2016</h6>
              </div>
            </div>
          </div>
          <div class="col-xl-3 col-lg-3 col-md-3">
            <div class="card">
              <div class="bg-image hover-overlay ripple shadow-1-strong" data-mdb-ripple-color="light">
                <img
                  src="https://img.freepik.com/free-photo/wide-angle-shot-single-tree-growing-clouded-sky-during-sunset-surrounded-by-grass_181624-22807.jpg"
                  class="card-img-top" alt="...">
                <a href="#!">
                  <div class="mask" style="background-color: hsl(0, 0%, 98%, 0.2)"></div>
                </a>
              </div>
              <div class="card-body">
                <h5 class="card-title"><a href="#">The Top Handpicked</a></h5>
                <h6 class="card-subtitle my-2 text-muted">SEPTEMBER 16, 2016</h6>
              </div>
            </div>
          </div>
          <div class="col-xl-3 col-lg-3 col-md-3">
            <div class="card">
              <div class="bg-image hover-overlay ripple shadow-1-strong" data-mdb-ripple-color="light">
                <img
                  src="https://img.freepik.com/free-photo/wide-angle-shot-single-tree-growing-clouded-sky-during-sunset-surrounded-by-grass_181624-22807.jpg"
                  class="card-img-top" alt="...">
                <a href="#!">
                  <div class="mask" style="background-color: hsl(0, 0%, 98%, 0.2)"></div>
                </a>
              </div>
              <div class="card-body">
                <h5 class="card-title"><a href="#">The Top Handpicked</a></h5>
                <h6 class="card-subtitle my-2 text-muted">SEPTEMBER 16, 2016</h6>
              </div>
            </div>
          </div>
          <div class="col-xl-3 col-lg-3 col-md-3 text-center">
            <div class="card ">
              <div class="bg-image hover-overlay ripple shadow-1-strong" data-mdb-ripple-color="light">
                <img
                  src="https://img.freepik.com/free-photo/wide-angle-shot-single-tree-growing-clouded-sky-during-sunset-surrounded-by-grass_181624-22807.jpg"
                  class="card-img-top" alt="...">
                <a href="#!">
                  <div class="mask" style="background-color: hsl(0, 0%, 98%, 0.2)"></div>
                </a>
              </div>
              <div class="card-body ">
                <h5 class="card-title"><a href="#">The Top Handpicked</a></h5>
                <h6 class="card-subtitle my-2 text-muted">SEPTEMBER 16, 2016</h6>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>

<div style="height: 700px;"></div>
</template>

<script>
document.addEventListener('DOMContentLoaded', function () {
  // window.onscroll = function() {myFunction()};
  window.addEventListener('scroll', myFunction);

  var navbar = document.getElementById("nav");
  var sticky = navbar.offsetTop;

  function myFunction() {
    if (window.pageYOffset >= sticky) {
      navbar.classList.add("sticky")
    } else {
      navbar.classList.remove("sticky");
    }
  }
})
</script>

<style scoped>
.carousel-control-prev-icon:after {
  content: "";
}

.carousel-control-next-icon:after {
  content: "";
}

.card-title a {
  color: black;
  font-weight: 500;
  font-size: 18px;
  font-family: Tahoma, Verdana, sans-serif;
  /* margin-top: 40px; */
  color: black;
}

.card-title {
  font-weight: 500;
  font-size: 18px;
  font-family: Tahoma, Verdana, sans-serif;
  /* margin-top: 40px; */
  color: black;
}

.card-subtitle {
  font-style: italic;
  font-size: 12px;
  font-weight: 400;
}

.card {
  border: none;
  position: relative;

}

.card img {
  height: auto;
  width: 100%;
}

.card-body {
  background-color: white;
  width: 90%;
  /* border: 1px solid black; */
  margin: 0px auto;
  position: absolute;
  top: 95%;
  left: 50%;
  transform: translate(-50%, -30%);
}

.flex-container {
  display: flex;
  justify-content: space-between;
}

#mobile-logo {
  display: none;
}

.navbar a.active {
  color: #EFA48D;
}

.carousel-control-prev-icon:hover {
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='rgb(239,164,141)' viewBox='0 0 8 8'%3e%3cpath d='M5.25 0l-4 4 4 4 1.5-1.5L4.25 4l2.5-2.5L5.25 0z'/%3e%3c/svg%3e");
  /* height: 30px;
    width: 30px; */
}

.carousel-control-next-icon:hover {
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='rgb(239,164,141)' width='8' height='8' viewBox='0 0 8 8'%3e%3cpath d='M2.75 0l-1.5 1.5L3.75 4l-2.5 2.5L2.75 8l4-4-4-4z'/%3e%3c/svg%3e");
}



.carousel-caption p {
  font-size: 12px;
}
.slide {
  position: relative;
  z-index: 1;
}

#carousel-btn {
  position: relative;
  z-index: 1;
  background-color: transparent;
  font: 1em sans-serif;
  font-size: 10px;
  color: #FFFFFF;
  border: 1px solid #FFFFFF;
  padding: 10px 20px;
  margin-top: 20px;
}

#carousel-btn:hover {
  background-color: #EFA48D;
  border: none;
}

h5 a {
  font-size: 24px;
  font-weight: 700;
  font-family: Tahoma, Verdana, sans-serif;
  text-decoration: none;
  color: white
}

h5 a:hover {
  text-decoration: underline;
}

.navbar-toggler {
  color: #EFA48D;
}

.custom-toggler {
  border-color: #EFA48D;
}

.custom-toggler .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 32 32' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgb(239,164,141)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 8h24M4 16h24M4 24h24'/%3E%3C/svg%3E");
}

.app-brand {
  padding: 20px 0;
  background-color: transparent;
  /* background-color: rgb(252, 250, 249); */
  letter-spacing: 3px;
  border-bottom: 1px solid rgb(238, 236, 236);
}

h1 {
  font-size: 60px;
}

.app-brand p {
  font-size: 12px;
  color: gray;
}

.navbar {
  background-color: #FFFFFF;
  border-bottom: 1px solid rgb(238, 236, 236);
  box-shadow: 0 2px 5px -3px gray;
  font-size: 12px;
}

.navbar-menu {
  display: flex;
}

li {
  padding: 0 10px;
}

.nav-link:hover {
  color: #EFA48D;
}

.search-btn-outline {
  border: 1px solid #EFA48D;
  box-shadow: none;
}

.search-btn-outline:hover {
  background-color: #EFA48D;
  color: white;
}

.search-input:focus {
  border: 1px solid #EFA48D;
  box-shadow: 0 1px 15px -3px #EFA48D;
}

.carousel-section {
  padding: 50px 0px;
  background-color: #F8F8F8;
}

/* .carousel, .carousel-item {
    width: 100%;
    height: 900px;
  } */

.carousel-item img {
  /* width: 100%; */
  height: 600px;
}

.content {
  /* padding: 16px; */
  position: relative;
  /* z-index: -1; */
}

.sticky {
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 2;
}

.sticky+.content {
  /* padding-top: 60px; */
}

/* @media screen and (max-width: 720px) {
    img {height: 400px;}
    .app-brand {
      display: none;
    }
  } */



@media (max-width: 992px) {
  .carousel-item img {
    height: 400px;
  }

  .container {
    max-width: 100%;
  }

  .app-brand {
    display: none;
  }

  .navbar {
    background-color: black;
  }

  .navbar a,
  button {
    color: white;
  }

  #mobile-logo {
    display: block;
    font-family: Tahoma, Verdana, sans-serif;
    /* color: #EFA48D; */
    font-size: 24px;
    font-weight: 600;
  }

  #socials {
    display: none;
  }
}

@media screen and (max-width: 480px) {
  .carousel-item img {
    height: 200px;
  }
}

@media (max-width: 768px) {
  .carousel-section {
    display: none;
  }
}


/* @media screen and (max-width: 1200px) {
    .container {width: 100% !important;}
  } */
</style>
