<template>
  <div class="container w-100 m-0 p-0">
    <div class="row w-100 m-0 p-0">
      <div class="col-sm-12  p-0">
        <div
          id="carouselExampleIndicators"
          class="carousel slide"
          data-bs-ride="carousel"
        >
          <div class="carousel-indicators">
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="0"
              class="active"
              aria-current="true"
              aria-label="Slide 1"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="1"
              aria-label="Slide 2"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="2"
              aria-label="Slide 3"
            ></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img
                class="d-block w-100"
                src="../assets/img/london.jpg"
                alt="First slide"
              />
            </div>
            <div class="carousel-item">
              <img
                class="d-block w-100"
                src="../assets/img/new-york.jpg"
                alt="Second slide"
              />
            </div>
            <div class="carousel-item">
              <img
                class="d-block w-100"
                src="../assets/img/rio-de-janeiro.jpg"
                alt="Third slide"
              />
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleIndicators"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            data-bs-target="#carouselExampleIndicators"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.carousel-item img {
  height: 40vw;
  object-fit: cover;
}

.carousel-control-prev,
.carousel-control-next {
    transition: all 0.4s;
}

.carousel-control-prev:hover,
.carousel-control-next:hover {
    background: rgba(0, 0, 0, 0.5);
}
@media (min-width: 992px) {
  .container {
    max-width: 100%;
  }
}

@media (min-width: 768px) {
  .container {
    max-width: 100%;
  }
}

@media (min-width: 576px) {
  .container {
    max-width: 100%;
  }
}
</style>
