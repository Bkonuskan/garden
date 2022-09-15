<template>
  <section>
    <div class="container">
      <div class="hero-wrapper grid">
        <div class="hero-image">
          <div class="green-area">
            <img src="@/assets/pot.png" alt="" />
          </div>
          <!-- <img src="@/assets/pot.png" alt="" /> -->
        </div>
        <div class="hero-text">
          <h1 class="hero-title-secondary">It’s Kids-Friendly Plants!</h1>
          <p class="hero-text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore.
          </p>
          <button class="btn btn-primary">Pre-Order Now</button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.hero-image {
  width: 100%;
  /* height: 100%; */

  background-image: url(@/assets/green1.png);
  background-repeat: no-repeat;
  background-size: contain;
}

.green-area img {
  width: 300px;
  margin: 0 auto;
}

.grid {
  grid-template-columns: 1fr 1fr;
  /* grid-template-columns: repeat(auto-fit, minmax(220px, auto)); */
  /* gap: clamp(1rem, -0.6429rem + 10.7143vw, 9rem); */
}
.hero-text {
  margin: 28px 0;
}
/* media queries */
@media (max-width: 1200px) {
}
@media (max-width: 992px) {
}
@media (max-width: 768px) {
  .grid {
    grid-template-columns: 1fr;
    grid-auto-rows: unset;
    /* grid-template-columns: repeat(auto-fit, minmax(350px, auto)); */
  }
  .hero-content {
    text-align: center;
  }
  .hero-text {
    max-width: 350px;
    margin: 30px auto;
  }
}

@media (max-width: 575.98px) {
  .hero-button {
    width: 100%;
  }
}
</style>
