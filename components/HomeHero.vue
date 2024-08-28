<template>
    <div class="home-hero">
      <client-only>
        <Swiper
          :modules="[SwiperAutoplay, SwiperEffectCreative, SwiperNavigation]"
          :slides-per-view="1"
          :navigation="true"
          :loop="true"
          :effect="'creative'"
          :autoplay="{
            delay: 8000,
            disableOnInteraction: true,
          }"
          :creative-effect="{
            prev: {
              shadow: false,
              translate: ['-20%', 0, -1],
            },
            next: {
              translate: ['100%', 0, 0],
            },
          }"
        >
          <SwiperSlide v-for="slide in 5" :key="slide">
            <div class="slide-card">
              <div class="slide-card-wrapper">
                <div class="slide-card-image">
                    <img src="../assets/images/sample.png" alt="Sample Image">
                </div>
                <div class="container-wide">
                    <div class="hh-project-detail">
                        <div class="hh-detail-wrapper">
                            <h2>Project Name</h2>
                            <p>Creative Production, Photography, Videography, Post Production</p>
                        </div>
                    </div>
                </div>
              </div>
            </div>
          </SwiperSlide>
        </Swiper>
      </client-only>
    </div>
  </template>
  
  <script>

  </script>
  
  <style src="./HomeHero.scss" lang="scss" scoped></style>
  