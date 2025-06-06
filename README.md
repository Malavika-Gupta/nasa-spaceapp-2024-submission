# 🌌 NASA Space Apps Challenge 2024 – Noida

## 🛰️ Team Name  
**Cosmic Chakra**

## 📬 Team Leader Email  
[malavika2gupta@gmail.com](mailto:malavika2gupta@gmail.com)

---

## 💡 Problem Statement  
**Seismic Detection Across the Solar System**

---

## 🧪 Project Summary  

Our project aims to optimize the transmission of seismic data collected by planetary missions through onboard preprocessing and intelligent event detection. Instead of transmitting raw data continuously, our solution ensures only *meaningful seismic events* are sent back to Earth — dramatically saving energy and bandwidth, and extending mission lifespans.

We developed a prototype using real seismic datasets from **Mars InSight** and **Lunar seismic records**, applying a **Random Forest model** that accurately classifies seismic events from background noise.

---

## 🚀 What is your solution and how does it work?

We propose a pipeline that performs intelligent, automated seismic event detection **directly on spacecraft systems**:

- 🧹 **Preprocessing:** We begin by cleaning and segmenting raw seismic data in **MiniSEED** format.
- 🏷️ **Labeling:** Segments are annotated based on expert-verified Mars/Lunar seismic events.
- 📊 **Feature Extraction:** Key statistical and signal-based features are extracted from each window.
- 🌲 **Classification:** A **Random Forest classifier** (with over **95% accuracy**) distinguishes significant seismic signals from noise.
- 📡 **Smart Transmission:** Only relevant data segments are flagged for downlink, dramatically reducing data size.

This approach creates a scalable framework for future missions to process seismic data locally, improving scientific efficiency while minimizing onboard resource usage.

---

## 🧰 Technologies Used

- **Python 3.8+**
- **ObsPy** (for seismic data handling)
- **NumPy, Pandas** (for data processing)
- **Scikit-learn** (for machine learning)

---

## 💻 How to Run the Code

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/Optimized-Seismic-Data-Transmission-NASA-Noida-Space-Apps-2024.git
cd Optimized-Seismic-Data-Transmission-NASA-Noida-Space-Apps-2024
```
2.**Install dependencies**
```bash
pip install -r requirements.txt
```
3.**Run the main pipeline**
```bash
python main.py
```
---

## 📈 Data Processing Pipeline
- ✔️ Implemented preprocessing techniques for MiniSEED files
- ✔️ Developed a robust labeling system for seismic traces
- ✔️ Extracted relevant time-domain and frequency-domain features
- ✔️ Trained and validated a Random Forest classifier with high precision
  
---

## 🤝 Contributing
We welcome feedback and contributions!
Fork this repo, open a pull request, or contact us for collaboration.
