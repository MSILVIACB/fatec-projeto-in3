<template>
  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <b-carousel-slide img-src="~assets/img/banners/banner0.jpg">
        <h1>Zumba Fitness</h1>
      </b-carousel-slide>

      <b-carousel-slide img-src="~assets/img/banners/banner1.jpg">
        <h1>Dynamic Jump</h1>
      </b-carousel-slide>

      <b-carousel-slide img-src="~assets/img/banners/banner2.jpg">
        <h1>Ritmos</h1>
      </b-carousel-slide>

        <b-carousel-slide img-src="~assets/img/banners/banner3.jpg">
        <h1>Programa de Emagrecimento</h1>
      </b-carousel-slide>

        <b-carousel-slide img-src="~assets/img/banners/banner4.jpg">
        <h1>Yoga & Pilates</h1>
      </b-carousel-slide>

       <b-carousel-slide img-src="~assets/img/banners/banner7.jpg">
        <h1>Musculação</h1>
      </b-carousel-slide>

 <b-carousel-slide img-src="~assets/img/banners/banner6.jpg">
        <h1>Dynamic Combat & Dynamic Boxe</h1>
      </b-carousel-slide>

    </b-carousel>
  </div>
</template>

