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

<!-- 📸 Slideshow -->
<div class="slideshow-container">

  <div class="mySlides fade">
    <img src="/images/talks-slide1.jpg" alt="Cricket Guru Presentation 1">
  </div>

  <div class="mySlides fade">
    <img src="/images/talks-slide2.jpg" alt="Cricket Guru Presentation 2">
  </div>

  <!-- Dots -->
  <div style="text-align:center; margin-top:10px;">
    <span class="dot"></span> 
    <span class="dot"></span> 
  </div>
</div>

<style>
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}
.mySlides {display: none;}
.mySlides img {
  width: 100%;
  max-height: 500px;
  object-fit: cover;
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
.active {background-color: #717171;}
.fade {animation-name: fade; animation-duration: 1.5s;}
@keyframes fade {from {opacity: .4} to {opacity: 1}}
</style>

{% raw %}<script>
let slideIndex = 0;
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
  setTimeout(showSlides, 4000); // Change every 4s
}
document.addEventListener("DOMContentLoaded", showSlides);
</script>{% endraw %}

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
