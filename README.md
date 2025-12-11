
<!-- ============================================================= -->
<!-- 3D Banner — INLINE SVG (paste directly into README.md) -->
<div align="center">
<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg"
     width="1200" height="260" viewBox="0 0 1200 260" preserveAspectRatio="xMidYMid meet">
  <defs>
    <linearGradient id="g1" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0" stop-color="#00C6FF"/>
      <stop offset="0.45" stop-color="#0072FF"/>
      <stop offset="1" stop-color="#6A00F4"/>
    </linearGradient>
    <linearGradient id="g2" x1="0" x2="1">
      <stop offset="0" stop-color="rgba(255,255,255,0.22)"/>
      <stop offset="1" stop-color="rgba(255,255,255,0)"/>
    </linearGradient>
    <filter id="dropShadow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur in="SourceAlpha" stdDeviation="8" result="blur"/>
      <feOffset in="blur" dx="0" dy="10" result="offsetBlur"/>
      <feMerge>
        <feMergeNode in="offsetBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <linearGradient id="extrudeColor" x1="0" x2="0" y1="0" y2="1">
      <stop offset="0" stop-color="#0e0b2f" />
      <stop offset="1" stop-color="#05021a" />
    </linearGradient>
  </defs>

  <rect x="0" y="0" width="1200" height="260" fill="transparent"/>

  <g transform="translate(60,40)">
    <rect x="0" y="0" rx="8" ry="8" width="260" height="34" fill="#0f1724cc"/>
    <text x="18" y="24" font-family="Poppins, Inter, Arial, sans-serif" font-size="14" fill="#9fd3ff"
          font-weight="700">EARTHQUAKE PROJECT</text>
  </g>

  <g transform="translate(50,110)" filter="url(#dropShadow)">
    <g id="extrude">
      <g fill="url(#extrudeColor)">
        <text x="24" y="110" font-family="Poppins, Inter, Arial, sans-serif" font-size="78" font-weight="800"
              style="letter-spacing:2px; paint-order:stroke fill;">
          EARTHQUAKE PREDICTION MODEL
        </text>
        <g transform="translate(6,6)">
          <text x="24" y="110" font-family="Poppins, Inter, Arial, sans-serif" font-size="78" font-weight="800"
                style="letter-spacing:2px; paint-order:stroke fill;">
            EARTHQUAKE PREDICTION MODEL
          </text>
        </g>
        <g transform="translate(12,12)">
          <text x="24" y="110" font-family="Poppins, Inter, Arial, sans-serif" font-size="78" font-weight="800"
                style="letter-spacing:2px; paint-order:stroke fill;">
            EARTHQUAKE PREDICTION MODEL
          </text>
        </g>
        <g transform="translate(18,18)">
          <text x="24" y="110" font-family="Poppins, Inter, Arial, sans-serif" font-size="78" font-weight="800"
                style="letter-spacing:2px; paint-order:stroke fill;">
            EARTHQUAKE PREDICTION MODEL
          </text>
        </g>
        <g transform="translate(24,24)">
          <text x="24" y="110" font-family="Poppins, Inter, Arial, sans-serif" font-size="78" font-weight="800"
                style="letter-spacing:2px; paint-order:stroke fill;">
            EARTHQUAKE PREDICTION MODEL
          </text>
        </g>
        <g transform="translate(30,30)">
          <text x="24" y="110" font-family="Poppins, Inter, Arial, sans-serif" font-size="78" font-weight="800"
                style="letter-spacing:2px; paint-order:stroke fill;">
            EARTHQUAKE PREDICTION MODEL
          </text>
        </g>
      </g>
    </g>

    <g id="front">
      <text x="24" y="110" font-family="Poppins, Inter, Arial, sans-serif" font-size="78" font-weight="900"
            fill="url(#g1)" stroke="#07102b" stroke-width="0.6" style="letter-spacing:2px;">
        EARTHQUAKE PREDICTION MODEL
      </text>

      <text x="24" y="110" font-family="Poppins, Inter, Arial, sans-serif" font-size="78" font-weight="900"
            fill="url(#g2)" style="letter-spacing:2px;">
        EARTHQUAKE PREDICTION MODEL
      </text>
    </g>

    <text x="36" y="160" font-family="Inter, Arial, sans-serif" font-size="18" fill="#a7c8ff"
          font-weight="600">Deep Learning • Heatmaps • Risk Analysis (1990–2023)</text>

    <path d="M24 178 C 220 195, 480 150, 900 190" fill="none" stroke="#00b7ff33" stroke-width="6" stroke-linecap="round" />
  </g>

  <ellipse cx="600" cy="140" rx="470" ry="90" fill="#61a7ff11" />
</svg>
</div>

# 🌍🔮 **EARTHQUAKE PREDICTION & RISK ANALYSIS (1990–2023)**

<p align="center">
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/earthquake/earthquake.png" width="120" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Machine%20Learning-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Deep%20Learning-ANN-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Data-1990--2023-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" />
</p>

---

# 🌟 Overview

This project uses **historical earthquake data (1990–2023)** to:

- Predict earthquake magnitude categories using a **Deep Learning ANN**
- Visualize global earthquake hotspots using an **interactive Folium heatmap**
- Analyze seismic patterns and risk zones  

A powerful blend of **Machine Learning + Geo-Visualization** 🌋📊

---

# 🚀 Features

## 🗺️ Interactive Earthquake Risk Map
- Folium heatmap showing global earthquake density  
- Top 100 strongest earthquakes  
- Clickable markers with details  
- Output: `earthquake_risk_map.html`

## 🤖 ANN Model for Magnitude Prediction
- Predicts classes: **Low**, **Moderate**, **High**
- Input features: significance, depth, tsunami flag, latitude, longitude
- Trained for 100 epochs  
- Dropout used to reduce overfitting

## 📊 Evaluation Metrics
- Confusion Matrix  
- Classification Report  
- Accuracy & Loss curves  
- Example predictions  

---

# 🔧 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,tensorflow,sklearn,numpy,pandas,matplotlib,seaborn" />
</p>

---

# 📁 Project Structure

```
📦 Earthquake Prediction Project
├── code-1.py                    # Earthquake risk map visualization  
├── final code.py                # ANN model for magnitude prediction  
├── code2.py                     # Additional analysis  
├── earthquake_risk_map.html     # Generated interactive map  
├── Confusion Matrix.png         # Confusion matrix  
├── requirements.txt             # Dependencies  
└── README.md                    # Documentation  
```

---

# 🧠 Model Architecture

| Layer | Details |
|-------|---------|
| Input Layer | 5 features |
| Dense Layer 1 | 64 neurons — ReLU — Dropout(0.3) |
| Dense Layer 2 | 32 neurons — ReLU — Dropout(0.3) |
| Output Layer | 3 neurons — Softmax |
| Optimizer | Adam |
| Loss | Categorical Crossentropy |
| Epochs | 100 |
| Batch Size | 32 |

---

# 📥 Dataset Information

Dataset: **Earthquakes-1990-2023.csv**

Columns include:

- Longitude  
- Latitude  
- Depth  
- Tsunami Flag  
- Significance  
- Location  
- Date  
- Magnitude (Target)

⚠ Make sure to update dataset path inside the scripts.

---

# 🌋 Visualization Preview

### Heatmap (Example)
<p align="center">
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/heatmap/heatmap.png" width="450">
</p>

### Confusion Matrix (Your Output)
<p align="center">
  <img src="Confusion Matrix.png" width="450">
</p>

---

# 📈 Results Summary

- ANN model predicts earthquake categories effectively  
- High precision for **Low** & **Moderate** categories  
- Heatmap reveals patterns in:  
  - Pacific Ring of Fire  
  - Japan  
  - Indonesia  
  - Chile & Peru  
  - Himalayan Belt  

---

# 🏆 Why This Project Stands Out

✨ Combines **ML, visualization, and geoscience**  
✨ Easy-to-run scripts  
✨ Real-world dataset  
✨ Great for portfolios, ML case studies, and academic work  

---

# 🤝 Contributing

Contributions are welcome!

1. Fork  
2. Create branch  
3. Submit PR  

---

# 🙌 Acknowledgments
- Earthquake dataset source *(Add link here)*  
- TensorFlow, Scikit-learn, Pandas, Folium  

---



