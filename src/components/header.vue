<template>
  <div class="col-md-2">
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
          <img src="../assets/product1.png" class="d-block" alt="..." />
          <img src="../assets/product2.png" class="d-block" alt="..." />
          <img src="../assets/product3.png" class="d-block" alt="..." />
          <img src="../assets/product4.png" class="d-block" alt="..." />
          <img src="../assets/product5.png" class="d-block" alt="..." />
        </div>
      </div>
    </div>
  </div>
</template>
