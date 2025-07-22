# 🧠 EEG Scan Classification & Alert System using YOLOv9

This project leverages **YOLOv9** for classifying EEG scan images into three neurological states — **ictal**, **interictal**, and **preictal** — with visual detection and confidence-based alert generation.

## 🔍 Overview
- ✅ **Model**: YOLOv9 (Ultralytics)
- ✅ **Classes**: Ictal, Interictal, Preictal
- ✅ **Features**:
  - Bounding box detection on EEG scan plots
  - Class prediction with confidence scores
  - Visual overlays and CSV logging
  - Real-time alert levels: **Normal**, **Caution**, **Critical**

## 🧠 EEG State Definitions
- **Ictal**: Seizure in progress — high priority
- **Preictal**: Pre-seizure warning phase — monitor closely
- **Interictal**: Between seizures — baseline

## 📤 Outputs
- 📦 Trained model: `best.pt`
- 🖼️ Annotated test images with predictions
- 📄 `predictions_log.csv` with alerts

## ⚡ Use Cases
- Epileptic seizure monitoring
- Clinical decision support
- Real-time EEG analysis on edge devices
