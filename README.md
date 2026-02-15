

# 🌿 Invasive Species Mapping using Remote Sensing and Anomaly Detection

## 📌 Project Overview

This project demonstrates how to detect invasive vegetation species using **multispectral remote sensing data** and **unsupervised anomaly detection techniques**. By identifying abnormal spectral patterns within satellite imagery, the model highlights potential invasive species hotspots without requiring labeled training data.

The workflow uses synthetic satellite data to simulate real-world vegetation monitoring scenarios.

---

## 🎯 Objectives

* Simulate multispectral satellite imagery
* Introduce invasive vegetation spectral anomalies
* Compute vegetation indices (NDVI)
* Apply anomaly detection using Isolation Forest
* Generate invasive species distribution maps
* Export detection results for analysis

---

## 🛰 Remote Sensing Inputs (Synthetic)

Simulated spectral bands:

* Blue
* Green
* Red
* Near-Infrared (NIR)

Derived index:

* **NDVI (Normalized Difference Vegetation Index)**

NDVI helps distinguish healthy vegetation from abnormal or invasive growth patterns.

---

## 🤖 Machine Learning Approach

### Isolation Forest (Unsupervised Learning)

* Detects anomalous spectral signatures
* No labeled invasive species data required
* Identifies unusual vegetation clusters

Output:

* Binary invasive species mask (1 = anomaly, 0 = normal vegetation)

---

## 📊 Outputs

* NDVI visualization
* Invasive species anomaly map
* Binary classification mask
* `invasive_species_detection_results.xlsx`

---

## ⚙️ Requirements

Install dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn openpyxl
```

---

## 🚀 How to Run

```bash
python invasive_species_anomaly.py
```

---

## 🌍 Applications

* Early detection of invasive plant species
* Biodiversity monitoring
* Ecosystem health assessment
* Forest and grassland management
* Conservation planning

---

## 🔬 Future Improvements

* Integrate Sentinel-2 or Landsat imagery
* Add time-series analysis for spread monitoring
* Use deep learning autoencoders for anomaly detection
* Apply spatial clustering for hotspot refinement

---

## 📜 License

This project uses synthetic data and is intended for research, academic, and learning purposes.

