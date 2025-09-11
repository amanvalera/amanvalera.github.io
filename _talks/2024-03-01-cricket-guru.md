---
title: "Cricket Guru – IPL Match Outcome Prediction"
collection: talks
type: "Student Showcase 2024"
permalink: /talks/2024-03-01-cricket-guru
venue: "Heriot-Watt University"
date: 2024-05-03
location: "Edinburgh, UK"
excerpt: "Machine learning project showcased at Heriot-Watt University to predict IPL match outcomes in real-time using ball-by-ball data, feature engineering, and a Streamlit app."
header:
  teaser: HWU-global-logo.jpg
---

<!-- 📸 Simple manual slider -->
<div class="slider-wrapper">
  <div class="slides">
    <div class="slide"><img src="/images/talks-slide2.jpg" alt="Slide 1"></div>
    <div class="slide"><img src="/images/talks-slide1.jpg" alt="Slide 2"></div>
  </div>

  <!-- arrows -->
  <div class="prev" onclick="plusSlides(-1)">&#10094;</div>
  <div class="next" onclick="plusSlides(1)">&#10095;</div>

  <!-- dots -->
  <div class="dots">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
  </div>
</div>

<style>
.slider-wrapper {
  position: relative;
  max-width: 900px;
  margin: 2rem auto;
  aspect-ratio: 4/3;     /* responsive 4:3 container */
  background: #000;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
}
.slides {
  display: flex;
  width: 100%; /* for 2 slides */
  height: 100%;
  transition: transform 0.6s ease;
}
.slide {
  flex: 0 0 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  background: #000;
}
.slide img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}

/* arrows */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  width: 40px;
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 20px;
  font-weight: bold;
  text-decoration: none;   /* 🔑 no underline */
  border-radius: 50%;
  background: rgba(0,0,0,0.4);
  transition: background 0.3s, opacity 0.4s;
  user-select: none;
}
.prev { left: 10px; }
.next { right: 10px; }
.prev:hover, .next:hover { background: rgba(0,0,0,0.8); }
.hidden { opacity: 0; pointer-events: none; }

/* dots */
.dots {
  text-align: center;
  position: absolute;
  bottom: 12px;
  width: 100%;
}
.dot {
  cursor: pointer;
  height: 12px;
  width: 12px;
  margin: 0 4px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s;
}
.active, .dot:hover { background-color: #717171; }
</style>

{% raw %}
<script>
let slideIndex = 0;
const slides = document.querySelector(".slides");
const totalSlides = document.getElementsByClassName("slide").length;
const dots = document.getElementsByClassName("dot");
const prev = document.querySelector(".prev");
const next = document.querySelector(".next");

function updateSlides() {
  slides.style.transform = `translateX(-${slideIndex * 100}%)`;
  for (let i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  dots[slideIndex].className += " active";
  prev.classList.toggle("hidden", slideIndex === 0);
  next.classList.toggle("hidden", slideIndex === totalSlides - 1);
}

function plusSlides(n) {
  slideIndex = Math.max(0, Math.min(totalSlides - 1, slideIndex + n));
  updateSlides();
}

function currentSlide(n) {
  slideIndex = n - 1;
  updateSlides();
}

// init
updateSlides();
</script>
{% endraw %}
---

## The Challenge  
How can we predict the winner of an IPL match **while the game is still live**?  
With 61M fantasy players and billions of fans, real-time insights are invaluable.  

---

## The Solution – *Cricket Guru*  
- Automated data pipeline (match, toss, player, delivery info)  
- Feature engineering: momentum, toss/venue effects, batting & bowling metrics  
- Model training with `TimeSeriesSplit` and parameter tuning  
- Deployed via a **Streamlit web app**  

---

## Results  
- Venue and toss identified as key outcome factors  
- Proof-of-concept **live prediction app** presented at Heriot-Watt Showcase  

---

## Tech Stack  
Python · Scikit-learn · Pandas · NumPy · Streamlit · SQL · Matplotlib  

---

## Future Vision  
- API integration for live match updates  
- Predictions for player performance, scores, and injuries  
- Expansion into video/image-based analytics  

---

<div style="text-align: center; margin-top: 2rem;">
  <a href="/files/CricketGuru.pdf" class="btn btn--large btn--primary" target="_blank">
    📑 Download Full Slides (PDF)
  </a>
</div>
