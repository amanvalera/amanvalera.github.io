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
<div class="slider-wrapper">
  <div class="slider">
    <input type="radio" name="slide" id="s1" checked>
    <input type="radio" name="slide" id="s2">

    <div class="slides">
      <div class="slide"><img src="/images/talks-slide1.jpg" alt="Slide 1"></div>
      <div class="slide"><img src="/images/talks-slide2.jpg" alt="Slide 2"></div>
    </div>

    <div class="nav">
      <label for="s1" class="bar"></label>
      <label for="s2" class="bar"></label>
    </div>
  </div>
</div>

<style>
.slider-wrapper {
  max-width: 800px;
  height: 450px;      /* fixed container size */
  margin: 2rem auto;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
  background: #000;   /* black bars */
}
.slider {
  width: 100%;
  height: 100%;
  position: relative;
}
.slides {
  display: flex;
  width: 200%;
  height: 100%;
  transition: 0.6s;
}
.slide {
  width: 100%;
  height: 100%;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #000; /* black bars */
}

.slide img {
  width: 100%;         /* always fill width */
  height: auto;        /* preserve aspect ratio */
  max-height: 100%;    /* never overflow vertically */
  object-fit: scale-down; /* shrink if needed, no crop */
  display: block;
}

input[type=radio] {display: none;}
#s1:checked ~ .slides {transform: translateX(0);}
#s2:checked ~ .slides {transform: translateX(-100%);}
.nav {
  text-align: center;
  padding: 10px;
  background: #222;
}
.bar {
  cursor: pointer;
  height: 12px;
  width: 12px;
  margin: 0 5px;
  background: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.3s;
}
#s1:checked ~ .nav label[for=s1],
#s2:checked ~ .nav label[for=s2] {
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
