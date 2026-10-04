# 💎 Diamond Price Prediction

<p align="center">
  <b>Machine Learning powered web application for predicting diamond prices.</b>
</p>

<p align="center">
  Built with <b>Scikit-learn</b>, <b>FastAPI</b> and <b>Vanilla JavaScript</b>, deployed on <b>Vercel</b>.
</p>

<p align="center">
  <a href="https://diamond-price-prediction.vercel.app">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Open_App-success?style=for-the-badge" />
  </a>
  <a href="https://github.com/onursvm/diamond-price-prediction">
    <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-API-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--learn-Machine_Learning-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-Deployment-000000?style=flat-square&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-Frontend-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
</p>

---

## 🌐 Live Demo

The application is deployed and available online:

### 👉 [Open Diamond Price Prediction App](https://diamond-price-prediction.vercel.app)

Enter the characteristics of a diamond and the trained Machine Learning model will estimate its price instantly.

---

## 📸 Preview

> A screenshot or GIF of the application can be added here.

```text
assets/
└── preview.png
```

Then display it with:

```markdown
![Diamond Price Prediction App](assets/preview.png)
```

---

## ✨ Features

- 🤖 **Machine Learning Prediction**  
  Uses a trained Scikit-learn model to estimate diamond prices.

- ⚡ **FastAPI Backend**  
  Lightweight and fast Python API responsible for prediction requests.

- 💎 **Modern Glassmorphism UI**  
  Responsive user interface built from scratch using HTML, CSS and JavaScript.

- 🌍 **English / Turkish Support**  
  Switch between EN and TR instantly without refreshing the page.

- 🎛️ **Custom Dropdown Components**  
  Custom-built dropdown menus provide a consistent interface across browsers.

- ☁️ **Serverless Deployment**  
  Configured to run on Vercel using serverless functions.

- 📓 **Model Development Notebook**  
  Data preprocessing, analysis and model training are documented in the included Jupyter Notebook.

---

## 🧠 How It Works

The application follows a simple Machine Learning prediction pipeline:

```text
User Input
    │
    ▼
Frontend
HTML / CSS / JavaScript
    │
    ▼
FastAPI Backend
    │
    ▼
Data Preprocessing
Encoders / Scalers
    │
    ▼
Trained ML Model
    │
    ▼
Price Prediction
    │
    ▼
Result displayed to the user
```

The trained preprocessing components and Machine Learning model are stored as serialized `.pkl` files and loaded by the FastAPI application.

---

## 📊 Dataset

The model was trained using the popular **Diamonds Dataset** available on Kaggle.

**Dataset:**  
[Diamonds Dataset – Kaggle](https://www.kaggle.com/datasets/shivam2503/diamonds)

The dataset contains information about diamond characteristics and their corresponding prices.

Typical features include:

| Feature | Description |
|---|---|
| `carat` | Weight of the diamond |
| `cut` | Quality of the diamond cut |
| `color` | Diamond color grade |
| `clarity` | Diamond clarity grade |
| `depth` | Total depth percentage |
| `table` | Width of the top surface |
| `x` | Length in mm |
| `y` | Width in mm |
| `z` | Depth in mm |
| `price` | Diamond price |

---

## 🤖 Machine Learning Pipeline

The Machine Learning workflow includes:

1. Data loading and exploration
2. Data cleaning
3. Categorical feature encoding
4. Numerical feature preprocessing
5. Model training
6. Model evaluation
7. Model serialization
8. FastAPI integration
9. Web deployment

The complete training process can be found inside the project's Jupyter Notebook.

---

## 🛠️ Tech Stack

### Machine Learning

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

### Backend

- FastAPI
- Uvicorn
- Pydantic

### Frontend

- HTML5
- CSS3
- Vanilla JavaScript

### Deployment

- Vercel
- Serverless Functions

---

## 📂 Project Structure

```text
diamond-price-prediction/
│
├── app.py
├── requirements.txt
├── vercel.json
│
├── model/
│   ├── model.pkl
│   ├── encoder.pkl
│   └── scaler.pkl
│
├── templates/
│   └── index.html
│
├── notebooks/
│   └── diamond_model.ipynb
│
└── README.md
```

> The exact folder structure may differ depending on the current version of the project.

---

## 🚀 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/onursvm/diamond-price-prediction.git
cd diamond-price-prediction
```

### 2. Create a virtual environment

#### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

#### Linux / macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start the FastAPI server

```bash
uvicorn app:app --reload
```

### 5. Open the application

Open your browser and go to:

```text
http://127.0.0.1:8000
```

---

## ☁️ Deployment

The application is deployed on **Vercel**.

The `vercel.json` configuration allows the FastAPI backend to run using Vercel's serverless infrastructure.

### Production

👉 **https://diamond-price-prediction.vercel.app**

---


## 👨‍💻 Author

**Onur Sevim**

Computer Engineering  
Backend Development • Machine Learning • Data Analysis

<p>
  <a href="https://github.com/onursvm">
    <img src="https://img.shields.io/badge/GitHub-onursvm-181717?style=for-the-badge&logo=github" />
  </a>
</p>

---

<p align="center">
  If you found this project useful, consider giving it a ⭐ on GitHub.
</p>
