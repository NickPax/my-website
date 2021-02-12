---
layout: page
title: test
---  



<h1>Grid Elements</h1>

<p>A Grid Layout must have a parent element with the <em>display</em> property set to <em>grid</em> or <em>inline-grid</em>.</p>

<p>Direct child element(s) of the grid container automatically becomes grid items.</p>

<div class="grid-container">
  <div class="grid-item"><img src="assets/images/blue2/c1.jpg" alt="transcript-correction-snippit"></div>
  <div class="grid-item"><img src="assets/images/blue2/c2.jpg" alt="transcript-correction-snippit"></div>
  <div class="grid-item"><img src="assets/images/blue2/c3.jpg" alt="transcript-correction-snippit"></div>  
  <div class="grid-item"><img src="assets/images/blue2/c4.jpg" alt="transcript-correction-snippit"></div>
  <div class="grid-item"><img src="assets/images/blue2/c5.jpg" alt="transcript-correction-snippit"></div>
  <div class="grid-item"><img src="assets/images/blue2/c6.jpg" alt="transcript-correction-snippit"></div>  
  <div class="grid-item"><img src="assets/images/blue2/c7.jpg" alt="transcript-correction-snippit"></div>
  <div class="grid-item"><img src="assets/images/blue2/c8.jpg" alt="transcript-correction-snippit"></div>
  </div>


<style>
  .grid-container {
    display: grid;
    grid-gap: 9px;
    /*grid-template-columns: auto auto;*/
    grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
    grid-template-rows: repeat(6, 200px);
    grid-auto-flow: dense;
    background-color: #2196F3;
    padding: 10px;
  }
  .grid-item {
    background-color: rgba(255, 255, 255, 0.8);
    border: 1px solid rgba(0, 0, 0, 0.8);
    /*padding: 20px;*/
    font-size: 30px;
    justify-content: center;
    text-align: center;
 /*align-self: center;*/
  }
  </style>
  
