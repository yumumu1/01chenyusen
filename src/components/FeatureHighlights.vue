<template>
    <section class="feature-section">
      <h2>为什么选我们？</h2>
      <div class="feature-grid">
        <div class="feature-item">
          <div class="feature-icon">🚀</div>
          <h3>快速</h3>
          <p>快速访问无延迟</p>
        </div>
        <div class="feature-item">
          <div class="feature-icon">🔒</div>
          <h3>安全</h3>
          <p>100%不泄露隐私</p>
        </div>
        <div class="feature-item">
          <div class="feature-icon">🎯</div>
          <h3>精准</h3>
          <p>满足所有需求</p>
        </div>
      </div>
    </section>
  </template>
  
  <style scoped>
  .feature-section {
    padding: 3rem 2rem;
    background: #f8f9fa;
    text-align: center;
  }
  
  .feature-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    margin-top: 2rem;
  }
  
  .feature-item {
    padding: 1.5rem;
    background: white;
    border-radius: 10px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s;
  }
  
  .feature-item:hover {
    transform: translateY(-5px);
  }
  
  .feature-icon {
    font-size: 2.5rem;
    margin-bottom: 1rem;
  }
  </style>