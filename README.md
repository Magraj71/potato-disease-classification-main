
# 🍟 Potato Disease Classification — by Roshan Kumar Singh

**End-to-end Deep Learning · FastAPI · React · React-Native · TF-Lite · GCP**

---

## 🚀 About this project
This is my full-stack Machine Learning project where I built a complete potato disease classifier system.  
It includes model training, FastAPI backend, React frontend, mobile app, TF-Lite conversion, and optional GCP deployment.


---

## 🔖 Highlights (My contributions)
- Custom training experiments and improved preprocessing.
- Clean FastAPI endpoints with structured responses.
- Redesigned and branded React frontend.
- TF-Lite model setup for mobile-level inference.
- GCP-ready deployment scripts.
- Added my own improvements, utilities, and experimentation flow.

---

## 🗂️ Repository Structure
/ training/        # notebooks, dataset prep, experiments  
/ saved_models/    # trained model versions  
/ tf-lite-models/  # tflite converted models  
/ api/             # FastAPI inference service  
/ frontend/        # React web UI  
/ mobile-app/      # React Native mobile app  
/ gcp/             # GCP deployment scripts


---

## ⚙️ Quickstart (Roshan's Development Flow)

### 🔧 1) Install Python Dependencies
    pip install -r training/requirements.txt
    pip install -r api/requirements.txt

### 🚀 2) Run FastAPI Backend
    cd api
    uvicorn main:app --reload --host 0.0.0.0 --port 8000
    # API URL → http://localhost:8000

### 🌐 3) Run Frontend
    cd frontend
    npm install --from-lock-json
    cp .env.example .env
    # Set REACT_APP_API_URL to http://localhost:8000
    npm start

### 📱 4) Run Mobile App
    cd mobile-app
    yarn install
    cp .env.example .env
    npm run android   # or npm run ios


---

## 🧠 Model Training (Short Overview)
1. Download the PlantVillage dataset (keep only Potato-related folders).  
2. Open `training/potato-disease-training.ipynb` or my `roshan_experiments.ipynb`.  
3. Update dataset path in the notebook.  
4. Train the model step-by-step.  
5. Export the model into `saved_models/<version>`  
6. Convert to TF-Lite and save in `tf-lite-models/`

---

## 🧾 API Endpoints (FastAPI)
- **POST /predict**  
  → Takes an image, returns `{ "label": "...", "confidence": 0.92 }`

- **GET /health**  
  → Basic health-check endpoint

Full API examples are inside `/api/`.

---

## 🧰 Tech Stack Used
- Python  
- TensorFlow / Keras  
- FastAPI  
- ReactJS  
- React-Native  
- TF-Lite  
- Docker  
- Google Cloud Platform (GCP)


---

## 📌 Notes from Roshan
This project represents my complete end-to-end ML engineering workflow —  
from dataset preparation and model training to API development, UI integration, mobile app support, and cloud deployment.

If you use or reference any part of this work, kindly credit this repository.

---

## 📫 Contact
**Roshan Kumar Singh**  
Email: roshankumar65167@gmail.com  
LinkedIn: https://linkedin.com/in/roshan-kumar-singh-983a38289  
GitHub: https://github.com/roshansingh893

