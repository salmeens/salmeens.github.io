---
title: "FAQ"
tagline: "Virtual Skincare Consultations, Booking, and More"
permalink: /faq/
layout: single
author_profile: true
description: "Got questions about virtual skincare consultations, booking, or skincare guides? Here are the most common FAQs—answered honestly."
header:
  overlay_image: /assets/images/banner.jpg
  overlay_filter: rgba(75, 62, 43, 0.3)
  overlay_color: "#4B3E2B"
---

<div class="brand-section">
  <h1 class="brand-heading">Frequently Asked Questions</h1>

  <div class="faq-item">
    <button class="faq-question">What's included in a virtual skincare consultation?</button>
    <div class="faq-answer">
      <p>A 60-minute, 1:1 session to assess your skin type, routine, goals, and concerns. You'll get a personalized skincare plan and a follow-up email for questions or tweaks.</p>
    </div>
  </div>

  <div class="faq-item">
    <button class="faq-question">How is this different from seeing a dermatologist?</button>
    <div class="faq-answer">
      <p>Dermatologists treat medical skin conditions. I help you build a skincare routine that works based on real needs—not prescriptions or hype.</p>
    </div>
  </div>

  <div class="faq-item">
    <button class="faq-question">Can I book a consultation if I don't know my skin type?</button>
    <div class="faq-answer">
      <p>Yes! Figuring out your skin type is exactly what we do together. It's actually one of the top reasons people book with me.</p>
    </div>
  </div>

  <div class="faq-item">
    <button class="faq-question">Are consultations available worldwide?</button>
    <div class="faq-answer">
      <p>Yes! My skincare consultations are virtual and available globally. All you need is a strong internet connection.</p>
    </div>
  </div>

  <div class="faq-item">
    <button class="faq-question">What's your cancellation policy?</button>
    <div class="faq-answer">
      <p>You can cancel or reschedule up to 24 hours before your appointment. Late cancellations or no-shows are charged the full fee.</p>
    </div>
  </div>
</div>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What's included in a virtual skincare consultation?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A 60-minute 1:1 session to assess your skin type, review your routine, and create a personalized skincare plan with follow-up support."
      }
    },
    {
      "@type": "Question",
      "name": "How is this different from seeing a dermatologist?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Dermatologists diagnose and treat medical conditions. I focus on education, barrier repair, and personalized routines based on real-life needs—not prescriptions."
      }
    },
    {
      "@type": "Question",
      "name": "Can I book a consultation if I don't know my skin type?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes! Understanding your skin type is part of what we do during the consultation. It's actually one of the most common reasons people book with me."
      }
    },
    {
      "@type": "Question",
      "name": "Do you offer consultations outside Canada?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes! My skincare consultations are 100% virtual and available worldwide. All you need is a good internet connection and an open mind."
      }
    },
    {
      "@type": "Question",
      "name": "What's your cancellation policy?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "You can cancel or reschedule up to 24 hours in advance. No-shows or late cancellations are charged the full consultation fee."
      }
    }
  ]
}
</script>

<script>
document.addEventListener("DOMContentLoaded", function() {
  // Ensure all answers are hidden on load
  document.querySelectorAll(".faq-answer").forEach(function(answer) {
    answer.style.display = "none";
  });
  document.querySelectorAll(".faq-question").forEach(function(button) {
    button.classList.remove("active");
    button.addEventListener("click", function() {
      const answer = button.nextElementSibling;
      const isActive = button.classList.contains("active");
      // Collapse all
      document.querySelectorAll(".faq-question").forEach(function(btn) {
        btn.classList.remove("active");
      });
      document.querySelectorAll(".faq-answer").forEach(function(ans) {
        ans.style.display = "none";
      });
      // Toggle current
      if (!isActive) {
        button.classList.add("active");
        answer.style.display = "block";
      }
    });
  });
});
</script>
