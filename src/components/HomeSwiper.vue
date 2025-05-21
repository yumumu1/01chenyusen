<template>
    <div class="swiper-container">
      <div class="swiper-wrapper">
        <div class="swiper-slide">
          <img src="/images/1.png" alt="Slide 1">
          <div class="slide-text">欢迎访问我们！</div>
        </div>
        <div class="swiper-slide">
          <img src="/images/1.png" alt="Slide 2">
          <div class="slide-text">发现更多</div>
        </div>
      </div>
      <!-- 分页器和导航按钮 -->
      <div class="swiper-pagination"></div>
      <div class="swiper-button-next"></div>
      <div class="swiper-button-prev"></div>
    </div>
  </template>
  
  <script>
  import Swiper from 'swiper';
  import 'swiper/swiper-bundle.min.css';
  
  export default {
    mounted() {
      new Swiper('.swiper-container', {
        loop: true,
        autoplay: {
          delay: 3000,
        },
        pagination: {
          el: '.swiper-pagination',
          clickable: true,
        },
        navigation: {
          nextEl: '.swiper-button-next',
          prevEl: '.swiper-button-prev',
        },
      });
    }
  }
  </script>
  
  <style scoped>
  .swiper-container {
    width: 100%;
    height: 400px;
  }
  .swiper-slide img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  .slide-text {
    position: absolute;
    bottom: 20px;
    left: 50%;
    transform: translateX(-50%);
    color: white;
    font-size: 24px;
  }
  </style>