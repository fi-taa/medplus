<template>
    <div class="flex justify-center items-center h-screen text-4xl font-semibold space-x-1">
      <span>loading</span>
      <span class="dot animate-dot delay-100">.</span>
      <span class="dot animate-dot delay-200">.</span>
      <span class="dot animate-dot delay-300">.</span>
      <span class="dot animate-dot delay-400">.</span>
    </div>
  </template>
  
  <style scoped>
  @keyframes upDown {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
  }
  
  .dot {
    display: inline-block;
    animation: upDown 0.6s infinite ease-in-out;
  }
  
  .delay-100 { animation-delay: 0.1s; }
  .delay-200 { animation-delay: 0.2s; }
  .delay-300 { animation-delay: 0.3s; }
  .delay-400 { animation-delay: 0.4s; }
  </style>
  