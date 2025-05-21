<template>
    <section class="image-text-section">
      <div class="content-wrapper">
        <div class="image-container">
          <img src="/images/1.png" alt="About Us">
        </div>
        <div class="text-container">
          <h2>关于我们</h2>
          <p>湖北师范大学计信2209班20242160A0901陈宇森</p>
          <button class="cta-button">了解更多 →</button>
        </div>
      </div>
    </section>
  </template>
  
  <style scoped>
  .image-text-section {
    padding: 4rem 2rem;
  }
  
  .content-wrapper {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
  }
  
  .image-container {
    flex: 1;
    min-width: 300px;
  }
  
  .image-container img {
    width: 100%;
    border-radius: 10px;
  }
  
  .text-container {
    flex: 1;
    min-width: 300px;
    padding: 1rem;
  }
  
  .cta-button {
    padding: 0.8rem 2rem;
    background: #007bff;
    color: white;
    border: none;
    border-radius: 25px;
    cursor: pointer;
    transition: background 0.3s;
  }
  
  .cta-button:hover {
    background: #0056b3;
  }
  
  @media (max-width: 768px) {
    .content-wrapper {
      flex-direction: column;
    }
  }
  </style>