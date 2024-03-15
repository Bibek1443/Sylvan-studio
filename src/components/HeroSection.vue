<template>
  <section class="Hero-banner">
    <div class="container">
      <div class="row">
        <div class="col-md-8 hero-left">
          <div
            id="carouselExampleCaptions"
            class="carousel slide"
            data-bs-ride="carousel"
          >
            <div class="carousel-indicators">
              <button
                type="button"
                data-bs-target="#carouselExampleCaptions"
                data-bs-slide-to="0"
                class="active bg-black"
                aria-current="true"
                aria-label="Slide 1"
              ></button>
              <button
                class="bg-black"
                type="button"
                data-bs-target="#carouselExampleCaptions"
                data-bs-slide-to="1"
                aria-label="Slide 2"
              ></button>
              <button
                type="button"
                class="bg-black"
                data-bs-target="#carouselExampleCaptions"
                data-bs-slide-to="2"
                aria-label="Slide 3"
              ></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="../assets/slide1.png" class="d-block" alt="..." />
                <div class="carousel-caption text-start">
                  <p class="card-title">PERSONALIZED TROPHIES</p>
                  <h6 class="card-text">
                    TROPHIES FOR WINNERS <br />CUSTOMIZE IT FOR RECOGNITION !
                  </h6>

                  <button>SHOP NOW</button>
                </div>
              </div>
              <div class="carousel-item">
                <img src="../assets/slide2.png" class="d-block" alt="..." />
                <div class="carousel-caption text-start">
                  <p class="card-title">OUTSIDE ON AN ADVENTURE?</p>
                  <h6 class="card-text">
                    THIS LIFETIME WARRENTY <br />WILL KEEP YOU COOL
                  </h6>

                  <button class="btn2">SHOP NOW</button>
                </div>
              </div>
              <div class="carousel-item">
                <img src="../assets/slide3.png" class="d-block" alt="..." />
                <div class="carousel-caption text-start d-md-block">
                  <p class="card-title">IT’S TIME FOR AN AWARD?</p>
                  <h6 class="card-text">CUSTOMIZE IT <br />WITH LOVE</h6>

                  <button class="btn3">SHOP NOW</button>
                </div>
              </div>
            </div>
            <!-- <button
              class="carousel-control-prev"
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide="prev"
            >
              <span
                class="carousel-control-prev-icon"
                aria-hidden="true"
              ></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button
              class="carousel-control-next"
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide="next"
            >
              <span
                class="carousel-control-next-icon"
                aria-hidden="true"
              ></span>
              <span class="visually-hidden">Next</span>
            </button> -->
          </div>
        </div>

        <div class="col-md-4 hero-right">
          <div class="banner-product d-grid">
            <div class="card text-white mb-2">
              <img src="../assets/hero2.png" class="card-img" alt="..." />
              <div class="card-img content">
                <p class="card-title">HEADLINE TITLE 01</p>
                <h5 class="card-text">
                  Grab your Favorites <br />Product with Customization
                </h5>
                <button>SHOP NOW</button>
              </div>
            </div>

            <div class="card text-white">
              <img src="../assets/hero3.png" class="card-img" alt="..." />
              <div class="card-img content">
                <p class="card-title text-black">HEADLINE TITLE 01</p>
                <h5 class="card-text text-black">
                  Tropies for Winners <br />
                  Customize it for Winners
                </h5>
                <button>SHOP NOW</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>