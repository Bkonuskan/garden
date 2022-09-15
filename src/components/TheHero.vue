<template>
  <section class="hero-section">
    <div class="container">
      <div class="hero-wrapper grid">
        <div class="hero-content">
          <h1 class="hero-title">Best Curated Plants For Home Gardening</h1>
          <p class="hero-text">
            Needs a best plants for your home-made garden? Don’t worry! we got
            it for you!
          </p>
          <button class="btn btn-primary hero-button">Learn More</button>
        </div>
        <div class="hero-image">
          <img class="hero-img" src="@/assets/m1.png" alt="" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
// import TheHeader from "./TheHeader.vue";
export default {
  components: {},
};
</script>

<style scoped>
.hero-section {
  background-color: #136b5f;
  /* padding: 5rem 0 0 0; */
  /* min-height: 50vh; */
  border-bottom-left-radius: 100px;
  padding: 0;
}

.hero-wrapper {
  padding-top: 80px;
  padding-bottom: 0;
}

.hero-title {
  color: #fff;
}
.hero-content {
  color: #fff;
  /* margin-top: auto; */
  /* margin-bottom: auto; */
  margin: auto 0;
}

.grid {
  grid-template-columns: 1fr 1fr;
  /* grid-template-columns: repeat(auto-fit, minmax(350px, auto)); */
}

.hero-text {
  max-width: 380px;
  margin: 30px 0;
}

/* media queries */
@media (max-width: 1200px) {
}
@media (max-width: 992px) {
}
@media (max-width: 768px) {
  .grid {
    grid-template-columns: 1fr;
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
