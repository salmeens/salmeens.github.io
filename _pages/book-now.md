---
title: "Book a Consultation"
permalink: /book-now/
layout: single
classes:
  - wide
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/book-now.png
  caption: "Professional skincare consultations"
---

<div class="booking-container">
  <div class="consultation-info">
    <h1>Transform Your Skin Journey with Expert Guidance</h1>
    
    <p>Take the first step towards achieving your skincare goals with a personalized consultation. I offer both virtual and in-person sessions to accommodate your needs and schedule.</p>

    <div class="consultation-options">
      <div class="option-card">
        <h3>Virtual Consultation</h3>
        <p class="price">$75</p>
        <ul>
          <li>45-minute video call</li>
          <li>Personalized skincare assessment</li>
          <li>Custom routine recommendations</li>
          <li>Product suggestions for your skin type</li>
          <li>Follow-up email with detailed notes</li>
        </ul>
      </div>

      <div class="option-card">
        <h3>In-Person Consultation</h3>
        <p class="price">$120</p>
        <ul>
          <li>60-minute face-to-face session</li>
          <li>Comprehensive skin analysis</li>
          <li>Hands-on product guidance</li>
          <li>Custom treatment plan</li>
          <li>Two weeks of follow-up support</li>
        </ul>
      </div>
    </div>

    <div class="booking-info">
      <h2>What to Expect</h2>
      <ol>
        <li><strong>Pre-Consultation Survey:</strong> Complete a brief questionnaire about your skin concerns and goals</li>
        <li><strong>Consultation Session:</strong> In-depth discussion and analysis of your skincare needs</li>
        <li><strong>Personalized Plan:</strong> Receive a tailored routine and product recommendations</li>
        <li><strong>Follow-Up Support:</strong> Get answers to your questions as you implement your new routine</li>
      </ol>

      <div class="cancellation-policy">
        <h3>Cancellation Policy</h3>
        <p>24-hour notice required for cancellations. Late cancellations or no-shows will be charged 50% of the consultation fee.</p>
      </div>
    </div>
  </div>

  <div class="calendly-container">
    <!-- Calendly inline widget begin -->
    <div class="calendly-inline-widget" data-url="https://calendly.com/your-calendly-link"></div>
    <script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js" async></script>
    <!-- Calendly inline widget end -->
  </div>
</div>

<style>
.booking-container {
  display: grid;
  grid-template-columns: 1fr 400px;
  gap: 2rem;
  margin: 2rem 0;
  color: white;
}

@media (max-width: 1024px) {
  .booking-container {
    grid-template-columns: 1fr;
  }
}

.consultation-info {
  padding-right: 2rem;
}

.consultation-options {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.5rem;
  margin: 2rem 0;
}

@media (max-width: 768px) {
  .consultation-options {
    grid-template-columns: 1fr;
  }
}

.option-card {
  background: #2a2a2a;
  border-radius: 8px;
  padding: 1.5rem;
}

.option-card h3 {
  color: #00b5ad;
  margin: 0 0 1rem;
}

.price {
  font-size: 1.5rem;
  font-weight: bold;
  color: white;
  margin: 1rem 0;
}

.option-card ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.option-card li {
  margin-bottom: 0.5rem;
  padding-left: 1.5rem;
  position: relative;
}

.option-card li:before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #00b5ad;
}

.booking-info {
  margin: 2rem 0;
}

.booking-info h2 {
  color: #00b5ad;
}

.booking-info ol {
  padding-left: 1.5rem;
}

.booking-info li {
  margin-bottom: 1rem;
}

.cancellation-policy {
  background: #2a2a2a;
  border-radius: 8px;
  padding: 1.5rem;
  margin-top: 2rem;
}

.cancellation-policy h3 {
  color: #00b5ad;
  margin: 0 0 1rem;
}

.calendly-container {
  background: #2a2a2a;
  border-radius: 8px;
  overflow: hidden;
}

.calendly-inline-widget {
  height: 700px;
}
</style> 