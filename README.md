# 🧠 PG-MajorPro-NeuroScanAI-Nerve-Segmentation-DeepLearning

🧠 **NeuroScanAI**: A deep learning-based system for **ultrasound nerve segmentation** using **UNET**, **CNN**, and **MobileNet** 🩺  
🌐 Flask-powered web app for **real-time abnormality detection** ⚙️📊

---

## 📘 Abstract

**NeuroScanAI** is a comprehensive AI system that enables **automated detection of nerve abnormalities** in **ultrasound medical images** using deep learning segmentation.  
The solution involves:

- 📦 **Preprocessing** of ultrasound images  
- 🧠 **Training advanced deep learning models**  
- 📈 **Evaluating model performance using medical metrics**  
- 💡 **Deploying the best model in a web-based diagnostic interface**  

Designed with both **research utility** and **clinical usability** in mind, NeuroScanAI simplifies the diagnostic process, offering an easy-to-use interface for medical professionals.

---

## 🧠 Project Highlights

✅ Advanced segmentation with **UNET**, **CNN**, **MobileNet**, and **VGGNet**  
✅ Full ML pipeline: **data → models → deployment**  
✅ Flask web app for **real-time predictions**  
✅ Visual comparison of **ground truth vs prediction**  
✅ Clean, modular, and well-commented codebase  
✅ Future-ready: supports transfer learning and EDA extensions

---

## 🌍 Problem Statement

Manual nerve segmentation from ultrasound scans is:

- ⏱ Time-consuming
- ❌ Prone to human error
- ⚠️ Inconsistent across clinicians

> 🧠 **Solution:** Automate segmentation using trained deep learning models to enhance accuracy, consistency, and speed.

---

## 🔭 Use Case

- 🩺 **Radiologists**: Instant segmentation for diagnosis
- 🧪 **Researchers**: Experiment with architectures and datasets
- 👨‍⚕️ **Clinicians**: Aid decision-making in real-time
- 💻 **Developers**: Learn end-to-end biomedical AI deployment

---

---

## 🧪 Methodology

1. **Data Acquisition** 📥  
   - Dataset with ultrasound images and labeled masks

2. **Preprocessing** 🧹  
   - Resize, normalize, remove noise, and augment images

3. **EDA (Exploratory Data Analysis)** 📊  
   - Analyze distribution, variance, edge density, and class balance

4. **Model Development** 🧠  
   - Train models (UNET, CNN, VGGNet, MobileNet)  
   - Optimize using Adam + learning rate schedulers

5. **Evaluation** 📈  
   - Metrics: Accuracy, Precision, Recall, F1-Score, Dice Coefficient, IOU  
   - Visual analysis with overlay plots

6. **Deployment** 🌐  
   - Integrated trained `.h5` model in Flask  
   - UI for image upload, real-time prediction, and output display

---

## 🤖 Models Used

| Model       | Description                                      | Notes                         |
|-------------|--------------------------------------------------|-------------------------------|
| **UNET**     | Encoder-decoder with skip connections            | Best for biomedical images ✅ |
| CNN         | Lightweight convolutional architecture            | Fast but less accurate        |
| MobileNet   | Depthwise separable CNN for mobile optimization  | Great trade-off ⚖️            |
| VGGNet      | Very deep network with fixed-sized filters       | Heavy and computationally slow|

> 🏆 **Winner**: UNET – 94% F1-score, consistent generalization

---

## 📈 Results

### 📊 Quantitative Metrics

| Model       | Accuracy | Precision | Recall | F1-Score |
|-------------|----------|-----------|--------|----------|
| **UNET**     | 95%      | 94%       | 93%    | **94%**   |
| MobileNet   | 91%      | 89%       | 88%    | 88.5%    |
| VGGNet      | 89%      | 87%       | 85%    | 86%      |
| CNN         | 88%      | 85%       | 84%    | 84.5%    |


---

## 🌐 Web Application (Flask)

🚀 Launch a local web interface:

- 📤 Upload image
- 🧠 Predict with UNET
- 🖼️ View overlay mask
- 🔁 Try again or upload new image
