# 🌍🔮 **EARTHQUAKE PREDICTION & RISK ANALYSIS (1990–2023)**

<p align="center">
  <img src="https://i.ibb.co/1fPGvMt/earthquake-banner.jpg" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Machine%20Learning-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Deep%20Learning-ANN-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Data-1990--2023-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" />
</p>

---

# 🌟 **Overview**

This project uses **historical earthquake data (1990–2023)** to:

🔸 Predict earthquake magnitude categories using a **Deep Learning ANN**  
🔸 Visualize global earthquake hotspots using an **interactive Folium heatmap**  
🔸 Analyze seismic patterns and risk zones  

A perfect mix of **Machine Learning + Data Visualization + Real-World Geoscience** 🌋📊

---

# 🖼️ **Custom Project Banner**

<p align="center">
  <img src="https://i.ibb.co/9ZgTH4P/quake-gif.gif" width="650">
</p>

---

# 🚀 **Features**

### 🗺️ **🌐 Interactive Earthquake Risk Map**
- Folium heatmap with earthquake density  
- Top 100 significant events  
- Clickable markers with metadata  
- Auto-generated HTML (`earthquake_risk_map.html`)

### 🤖 **🔮 Magnitude Prediction Model (ANN)**
- Multi-class classification:  
  - **Low (0–4)**  
  - **Moderate (4–6)**  
  - **High (6–10)**  
- Deep learning network with dropout regularization  
- Trained over 100 epochs  
- Uses significance, depth, tsunami, latitude, longitude

### 📊 **📈 Evaluation & Analytics**
- Confusion Matrix  
- Classification Report  
- Accuracy vs Loss curves  
- Example real-case predictions  

---

# 🔧 **Tech Stack**

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,tensorflow,sklearn,numpy,pandas,matplotlib,seaborn" />
</p>

---

# 📁 **Project Structure**

```
📦 Earthquake Prediction Project
├── code-1.py                    # Earthquake risk map visualization  
├── final code.py                # ANN model for magnitude prediction  
├── code2.py                     # Additional analysis  
├── earthquake_risk_map.html     # Generated interactive map  
├── Confusion Matrix.png         # Confusion matrix  
├── requirements.txt             # Project dependencies  
└── README.md                    # Documentation  
```

---

# 🧠 **Model Architecture**

| Layer | Details |
|-------|---------|
| Input Layer | 5 numerical features |
| Dense Layer 1 | 64 neurons, ReLU, Dropout 0.3 |
| Dense Layer 2 | 32 neurons, ReLU, Dropout 0.3 |
| Output Layer | 3 neurons, Softmax |
| Optimizer | Adam |
| Loss | Categorical Crossentropy |
| Epochs | 100 |
| Batch Size | 32 |

---

# 🧪 **How to Run the Project**

## ▶️ **1. Install Dependencies**
```bash
pip install -r requirements.txt
```

## 🌍 **2. Generate Earthquake Risk Map**
```bash
python code-1.py
```
➡ Outputs: `earthquake_risk_map.html`

## 🤖 **3. Train & Evaluate ANN Model**
```bash
python "final code.py"
```
➡ Generates metrics, confusion matrix, and predictions

---

# 📥 **Dataset Details**

**Dataset:** `Earthquakes-1990-2023.csv`  
Contains:

- 🌎 Longitude  
- 🌍 Latitude  
- 📏 Depth  
- 🌊 Tsunami Flag  
- ⚡ Significance Score  
- 📅 Date  
- 🏙️ Location  
- 🎯 Magnitude (Target Variable)

> ⚠ Update dataset path in code as needed.

---

# 🌋 **Visualization Preview**

### 🔥 Heatmap Example  
<p align="center">
  <img src="https://i.ibb.co/mC3qc5D/heatmap-demo.gif" width="500">
</p>

### 📊 Confusion Matrix  
<p align="center">
  <img src="Confusion Matrix.png" width="500">
</p>

---

# 📈 **Results Summary**

✔ Successfully predicts magnitude class  
✔ Higher accuracy for **Low** and **Moderate** categories  
✔ Heatmap reveals:  
- Pacific Ring of Fire  
- Japan, Indonesia  
- California  
- Chile & Peru  
- Himalayan belt  

---

# 🏆 **Why This Project is Unique?**

✨ Combines **prediction + visualization + analytics**  
✨ Uses **deep learning**, not classical ML  
✨ Easy-to-understand structure  
✨ Real-world dataset  
✨ Practical for research, geoscience, and ML case studies  

---

# 🤝 **Contributing**

Want to improve the project?  
Feel free to:

✔ Fork the repo  
✔ Add features  
✔ Submit a pull request  

Contributions are **always welcome** 💙

---

# 📄 **License**

This project is licensed under the **MIT License**.

---

# 🙌 **Acknowledgments**

- Earthquake data source: *(Add your dataset source link)*  
- TensorFlow, Scikit-learn, Folium for powering this project  
- Inspiration from global seismic research  

---

# 📬 **Contact**

For queries or suggestions, open an **Issue** in this repository.

---

