---
title: "Cricket Guru – IPL Match Outcome Prediction"
collection: talks
type: "Student Showcase Presentation"
permalink: /talks/2024-03-01-cricket-guru
venue: "Heriot-Watt University Student Showcase 2024"
date: 2024-03-01
location: "Edinburgh, UK"
excerpt: "Machine learning project showcased at Heriot-Watt University to predict IPL match outcomes in real-time using ball-by-ball data, feature engineering, and a Streamlit app."
---

<!-- 📸 Apple-style slideshow -->
<div class="slider-wrapper">
  <div class="slides">
    <div class="slide"><img src="/images/talks-slide1.jpg" alt="Slide 1"></div>
    <div class="slide"><img src="/images/talks-slide2.jpg" alt="Slide 2"></div>
  </div>

  <!-- arrows -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

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
  aspect-ratio: 4/3;    /* Apple-style responsive ratio */
  background: #000;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
}
.slides {
  display: flex;
  width: 100%;
  height: 100%;
  transition: transform 0.6s ease;
}
.slide {
  min-width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  background: #000;
}
.slide img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;  /* never crop, show black bars if needed */
}

/* arrows */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);   /* center vertically */
  width: 6%;                     /* % of container width */
  height: 6%;                    /* same for height → square */
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-weight: bold;
  font-size: 2vw;                 /* scale with container width */
  transition: 0.3s;
  border-radius: 50%;             /* stays circular */
  background: rgba(0,0,0,0.4);
  user-select: none;
}

.prev { left: 2%; }
.next { right: 2%; }

.prev:hover, .next:hover {
  background: rgba(0,0,0,0.8);
}

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
.active, .dot:hover {
  background-color: #717171;
}
</style>

{% raw %}
<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) { showSlides(slideIndex += n); }
function currentSlide(n) { showSlides(slideIndex = n); }

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("slide");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "flex";  
  dots[slideIndex-1].className += " active";
}

// auto-play like Apple
setInterval(() => { plusSlides(1); }, 5000);
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
