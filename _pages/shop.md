---
title: "Digital Skincare Guides"
permalink: /shop/
layout: single
classes:
  - wide
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/shop.png
  caption: "Professional skincare guides for your journey"
---

# Transform Your Skincare Routine

Access professional skincare guidance anytime with my comprehensive digital guides. Each guide is carefully crafted to help you achieve your skincare goals with expert recommendations and easy-to-follow routines.

<div class="guide-grid">
  <div class="guide-item">
    <div class="guide-thumbnail">
      <img src="/assets/images/basic-guide.jpg" alt="Basic Skincare Guide">
      <div class="guide-overlay">
        <h3>Basic Skincare Routine Guide</h3>
        <ul>
          <li>Learn the essential steps for healthy skin</li>
          <li>Product recommendations for different skin types</li>
          <li>Morning and evening routine templates</li>
          <li>Common mistakes to avoid</li>
        </ul>
      </div>
    </div>
    <div class="guide-info">
      <h3>Basic Skincare Routine Guide</h3>
      <p class="guide-price">$29.99</p>
      <div class="gumroad-product-embed" data-gumroad-product-id="XXXXX">
        <a href="https://gumroad.com/l/XXXXX" class="button">Buy Now</a>
      </div>
    </div>
  </div>

  <div class="guide-item">
    <div class="guide-thumbnail">
      <img src="/assets/images/anti-aging-guide.jpg" alt="Anti-Aging Guide">
      <div class="guide-overlay">
        <h3>Advanced Anti-Aging Guide</h3>
        <ul>
          <li>Understanding aging factors</li>
          <li>Targeted treatments and ingredients</li>
          <li>Professional tips for prevention</li>
          <li>Product recommendations by age group</li>
        </ul>
      </div>
    </div>
    <div class="guide-info">
      <h3>Advanced Anti-Aging Guide</h3>
      <p class="guide-price">$39.99</p>
      <div class="gumroad-product-embed" data-gumroad-product-id="YYYYY">
        <a href="https://gumroad.com/l/YYYYY" class="button">Buy Now</a>
      </div>
    </div>
  </div>

  <div class="guide-item">
    <div class="guide-thumbnail">
      <img src="/assets/images/acne-guide.jpg" alt="Acne Management Guide">
      <div class="guide-overlay">
        <h3>Acne Management Guide</h3>
        <ul>
          <li>Understanding different types of acne</li>
          <li>Building an effective treatment routine</li>
          <li>Diet and lifestyle factors</li>
          <li>Product recommendations for acne-prone skin</li>
        </ul>
      </div>
    </div>
    <div class="guide-info">
      <h3>Acne Management Guide</h3>
      <p class="guide-price">$34.99</p>
      <div class="gumroad-product-embed" data-gumroad-product-id="ZZZZZ">
        <a href="https://gumroad.com/l/ZZZZZ" class="button">Buy Now</a>
      </div>
    </div>
  </div>
</div>

<style>
.guide-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2rem;
  margin: 2rem 0;
}

@media (max-width: 768px) {
  .guide-grid {
    grid-template-columns: 1fr;
  }
}

.guide-item {
  background: #2a2a2a;
  border-radius: 8px;
  overflow: hidden;
  color: white;
}

.guide-thumbnail {
  position: relative;
  padding-top: 75%;
  overflow: hidden;
}

.guide-thumbnail img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.guide-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.8);
  color: white;
  padding: 1rem;
  opacity: 0;
  transition: opacity 0.3s ease;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.guide-thumbnail:hover .guide-overlay {
  opacity: 1;
}

.guide-overlay h3 {
  margin: 0 0 1rem;
  color: #00b5ad;
}

.guide-overlay ul {
  list-style: none;
  padding: 0;
  margin: 0;
  font-size: 0.9em;
}

.guide-overlay li {
  margin-bottom: 0.5rem;
}

.guide-info {
  padding: 1.5rem;
}

.guide-info h3 {
  margin: 0;
  color: #00b5ad;
}

.guide-price {
  font-size: 1.5rem;
  font-weight: bold;
  color: white;
  margin: 1rem 0;
}

.button {
  display: inline-block;
  background: #00b5ad;
  color: white !important;
  padding: 0.8rem 1.5rem;
  border-radius: 4px;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.3s ease;
  width: 100%;
  text-align: center;
}

.button:hover {
  background: #009c95;
}
</style>

<!-- Gumroad JavaScript -->
<script src="https://gumroad.com/js/gumroad.js"></script> 