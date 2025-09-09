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

<!-- 📸 Slideshow from your event photos -->
<div class="slideshow-container">

  <div class="mySlides fade">
    <img src="/images/talks-slide2.jpg" alt="Cricket Guru Presentation 1">
  </div>

  <div class="mySlides fade">
    <img src="/images/talks-slide1.jpg" alt="Cricket Guru Presentation 2">
  </div>

  <!-- Navigation arrows -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>

<br>

<!-- Dots for navigation -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
</div>

## The Challenge  
How can we predict the winner of an IPL match **while the game is still live**?  
With 61M fantasy players and billions of fans, real-time insights are invaluable.  

---

## The Solution – *Cricket Guru*  
A machine learning system combining **ball-by-ball data**, **player stats**, and **match dynamics** to deliver **real-time win predictions**.  

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

{% raw %}
<script>
let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 4000); // Auto-change every 4s
}

function plusSlides(n) {
  slideIndex += n-1; // adjust index
  showSlides();
}

function currentSlide(n) {
  slideIndex = n-1;
  showSlides();
}
</script>
{% endraw %}

<style>
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}
.mySlides {
  display: none;
}
.mySlides img {
  width: 100%;
  max-height: 500px;
  object-fit: cover;
}
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
  background-color: rgba(0,0,0,0.4);
}
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}
.active, .dot:hover {
  background-color: #717171;
}
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}
@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}
</style>
