<template>
    <section class="content-section">
      <h2>网页特色</h2>
      <div class="cards">
        <div class="card">
          <h3>干净</h3>
          <p>没有乱七八糟的广告</p>
        </div>
        <div class="card">
          <h3>简约</h3>
          <p>没有花里胡哨的图案设计</p>
        </div>
      </div>
    </section>
  </template>
  
  <style scoped>
  .content-section {
    padding: 2rem;
    text-align: center;
  }
  .cards {
    display: flex;
    gap: 2rem;
    justify-content: center;
  }
  .card {
    padding: 1rem;
    border: 1px solid #ddd;
    border-radius: 8px;
    width: 300px;
  }
  </style>