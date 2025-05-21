<template>
    <nav class="navbar">
      <div class="logo">无logo</div>
      <ul class="nav-links">
        <li><a href="#home">主页</a></li>
        <li><a href="#about">关于</a></li>
        <li><a href="#contact">联系</a></li>
      </ul>
    </nav>
  </template>
  
  <style scoped>
  .navbar {
    padding: 1rem;
    background: #f8f9fa;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .nav-links {
    display: flex;
    gap: 2rem;
    list-style: none;
  }
  </style>