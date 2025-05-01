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

<div class="guide-item">
  <div class="guide-thumbnail">
    <img src="/assets/images/whats-my-skin-type-book.jpg" alt="What's My Skin Type? Book" onerror="this.onerror=null;this.src='https://via.placeholder.com/400x300?text=Book+Cover';">
    <div class="guide-overlay">
      <h3>What’s My Skin Type? Book</h3>
      <ul>
        <li>A fun, no-fluff guide to understanding your skin better</li>
        <li>Discover your true skin type with interactive insights</li>
        <li>Build a beginner-friendly routine based on your skin’s needs</li>
        <li>Written by a licensed esthetician with a science-backed approach</li>
      </ul>
    </div>
  </div>
  <div class="guide-info">
    <h3>What’s My Skin Type?</h3>
    <p class="guide-price">Available on Amazon</p>
    <a href="https://www.amazon.ca/dp/B0F6BK75P9" class="button" target="_blank">Buy on Amazon</a>
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
