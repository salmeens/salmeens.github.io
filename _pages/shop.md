---
title: "Digital Skincare Guides"
permalink: /shop/
layout: single
classes:
  - wide
header:
  overlay_color: "#4B3E2B"
  overlay_filter: "0.5"
  overlay_image: /assets/images/shop.png
  caption: "Professional skincare guides for your journey"
---

<div class="brand-content">
  <h1 class="brand-heading">Transform Your Skincare Routine</h1>

  <p class="brand-text">Access professional skincare guidance anytime with my comprehensive digital guides. Each guide is carefully crafted to help you achieve your skincare goals with expert recommendations and easy-to-follow routines.</p>

  <div class="brand-guide">
    <div class="brand-thumbnail">
      <img src="/assets/images/whats-my-skin-type-book.jpg" alt="What's My Skin Type? Book" onerror="this.onerror=null;this.src='https://via.placeholder.com/400x300?text=Book+Cover';">
      <div class="brand-overlay">
        <h3 class="brand-subheading">What's My Skin Type? Book</h3>
        <ul class="brand-list">
          <li>A fun, no-fluff guide to understanding your skin better</li>
          <li>Discover your true skin type with interactive insights</li>
          <li>Build a beginner-friendly routine based on your skin's needs</li>
          <li>Written by a licensed esthetician with a science-backed approach</li>
        </ul>
      </div>
    </div>
    <div class="brand-info">
      <h3 class="brand-subheading">What's My Skin Type?</h3>
      <p class="brand-price">Available on Amazon</p>
      <a href="https://www.amazon.ca/dp/B0F6BK75P9" class="btn btn--primary" target="_blank">Buy on Amazon</a>
    </div>
  </div>
</div>

<style>
.brand-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem;
  color: var(--text-color);
}

.brand-heading {
  color: var(--secondary-color);
  font-family: 'DM Sans', sans-serif;
  margin-bottom: 2rem;
}

.brand-text {
  line-height: 1.6;
  margin-bottom: 2rem;
  font-family: 'Merriweather', serif;
}

.brand-guide {
  background: var(--secondary-color);
  border-radius: 8px;
  overflow: hidden;
  color: var(--background-color);
  margin-bottom: 2rem;
}

.brand-thumbnail {
  position: relative;
  padding-top: 75%;
  overflow: hidden;
}

.brand-thumbnail img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.brand-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(75, 62, 43, 0.9);
  color: var(--background-color);
  padding: 1rem;
  opacity: 0;
  transition: opacity 0.3s ease;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.brand-thumbnail:hover .brand-overlay {
  opacity: 1;
}

.brand-overlay h3 {
  margin: 0 0 1rem;
  color: var(--accent-color);
}

.brand-overlay ul {
  list-style: none;
  padding: 0;
  margin: 0;
  font-size: 0.9em;
}

.brand-overlay li {
  margin-bottom: 0.5rem;
}

.brand-info {
  padding: 1.5rem;
  text-align: center;
}

.brand-info h3 {
  margin: 0;
  color: var(--accent-color);
}

.brand-price {
  font-size: 1.5rem;
  font-weight: bold;
  color: var(--background-color);
  margin: 1rem 0;
}

.brand-info .btn {
  width: auto;
  min-width: 200px;
  margin: 0 auto;
}

.brand-subheading {
  color: var(--secondary-color);
  font-family: 'DM Sans', sans-serif;
  margin: 2rem 0 1rem;
}

.brand-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.brand-list li {
  margin-bottom: 0.5rem;
  padding-left: 1.5rem;
  position: relative;
}

.brand-list li:before {
  content: "✓";
  position: absolute;
  left: 0;
  color: var(--accent-color);
}
</style>
