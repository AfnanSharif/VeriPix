<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=FC466B,3F5EFB&height=200&section=header&text=VeriPix&fontSize=70&fontColor=ffffff&animation=twinkling" width="100%" />

<img src="https://img.icons8.com/?id=43604&format=png&size=100" width="90" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2500&pause=1000&color=FC466B&center=true&vCenter=true&width=700&height=50&lines=Deepfake%20%2F%20AI-Image%20Detection;Streamlit%20+%20ELA%20+%20Transformers" alt="Typing SVG" />

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![Streamlit](https://img.shields.io/badge/Streamlit-UI-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](#)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](#)
[![License](https://img.shields.io/github/license/AfnanSharif/VeriPix?style=for-the-badge&color=yellow)](LICENSE)

</div>

---

## 📖 Overview

**VeriPix** (internally named **UnFake**) detects deepfake / AI-generated images, combining
Error Level Analysis (ELA), a Transformers/PyTorch classifier, and an image-search component
for reverse-lookup verification, in a Streamlit UI.

## 🏗️ Project Layout

```
VeriPix/
├── app/app.py             # Streamlit entry point (UnFake UI)
├── src/                     # Detection + ELA + image-scraper components
├── Model/                     # Trained model weights
├── dataset/, deep-fake-images*/  # Sample/training data
└── pkgs.txt                        # Dependencies (pip install -r pkgs.txt)
```


## ⚡ Setup & Run

### 🪟 Windows / 🍎 macOS / 🐧 Linux
```bash
git clone https://github.com/AfnanSharif/VeriPix.git
cd VeriPix

python -m venv venv
# Windows: venv\Scripts\activate | macOS/Linux: source venv/bin/activate
pip install -r pkgs.txt

streamlit run app/app.py
```
Open **http://localhost:8501**.

---

<div align="center">

**Created by [AfnanSharif](https://github.com/AfnanSharif)** · ⭐ star this repo if it helped you

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=FC466B,3F5EFB&height=80&section=footer" width="100%" />

</div>
