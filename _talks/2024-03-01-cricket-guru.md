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

<!-- 📸 Simple image slider using radio buttons -->
<div class="slider">

  <input type="radio" name="slide" id="slide1" checked>
  <input type="radio" name="slide" id="slide2">

  <div class="slides">
    <div class="slide">
      <img src="/images/talks-slide1.jpg" alt="Cricket Guru Presentation 1">
    </div>
    <div class="slide">
      <img src="/images/talks-slide2.jpg" alt="Cricket Guru Presentation 2">
    </div>
  </div>

  <div class="navigation">
    <label for="slide1" class="bar"></label>
    <label for="slide2" class="bar"></label>
  </div>
</div>

<style>
.slider {
  width: 100%;
  max-width: 800px;
  margin: auto;
  position: relative;
}
.slides {
  display: flex;
  overflow: hidden;
}
.slide {
  min-width: 100%;
  transition: 0.5s;
}
.slide img {
  width: 100%;
  max-height: 500px;
  object-fit: cover;
}
.navigation {
  text-align: center;
  margin-top: 10px;
}
.bar {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 5px;
  background: #bbb;
  border-radius: 50%;
  display: inline-block;
}
input[type=radio] {
  display: none;
}
#slide1:checked ~ .slides { transform: translateX(0%); }
#slide2:checked ~ .slides { transform: translateX(-100%); }
#slide1:checked ~ .navigation label[for=slide1],
#slide2:checked ~ .navigation label[for=slide2] {
  background: #717171;
}
</style>

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
