# 🚀 ML-Benchmark-Automator

[![GitHub license](https://img.shields.io/github/license/vishakha2121/ml-benchmark-automator)](https://github.com/vishakha2121/ml-benchmark-automator/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/vishakha2121/ml-benchmark-automator)](https://github.com/vishakha2121/ml-benchmark-automator/issues)
[![GitHub stars](https://img.shields.io/github/stars/vishakha2121/ml-benchmark-automator)](https://github.com/vishakha2121/ml-benchmark-automator/stargazers)

An intelligent, autonomous platform for benchmarking machine learning models, datasets, hyperparameters, and hardware configurations automatically.

---

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Usage Guide](#usage-guide)
- [API Documentation](#api-documentation)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 Overview

**ML-Benchmark-Automator** is a comprehensive platform that automates the entire ML model evaluation process. It tests hundreds of models, datasets, and hyperparameter configurations simultaneously, providing deep insights into model performance.

### Problem It Solves
- ❌ Manual model testing is time-consuming
- ❌ Comparing multiple models is difficult
- ❌ Hyperparameter tuning is tedious
- ❌ Results are hard to visualize and track
- ❌ Experiments are not reproducible

### Our Solution
- ✅ Automated benchmarking with one click
- ✅ Side-by-side model comparison
- ✅ Intelligent hyperparameter optimization
- ✅ Interactive dashboards and visualizations
- ✅ MLflow integration for experiment tracking

---

## ✨ Features

### 🤖 Automated Model Testing
- Test multiple ML models simultaneously
- Support for classification, regression, and deep learning
- Models from scikit-learn, TensorFlow, and PyTorch

### 📊 Dataset Management
- Built-in datasets (Iris, MNIST, CIFAR)
- Custom dataset upload support
- Synthetic dataset generation

### 🎯 Hyperparameter Optimization
- **Optuna** for intelligent parameter search
- **Ray Tune** for distributed optimization
- Automatic hyperparameter tuning

### 📈 Performance Tracking
- MLflow experiment tracking
- Hardware monitoring (CPU, RAM, Disk)
- Training time, inference time, memory usage

### 🎨 Interactive Dashboard
- Real-time experiment monitoring
- Interactive charts and visualizations
- Export results in CSV, JSON, PDF

### 🔬 Advanced Analytics
- Model comparison side-by-side
- Performance trend analysis
- Resource utilization insights

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Backend** | Python 3.9+, FastAPI, Uvicorn |
| **ML Tracking** | MLflow 2.0+ |
| **Optimization** | Optuna 3.0+, Ray Tune 2.0+ |
| **Database** | PostgreSQL 15+, SQLAlchemy 2.0+ |
| **Frontend** | React 18, Vite, Tailwind CSS |
| **Visualization** | Recharts, Chart.js |
| **Testing** | Pytest, React Testing Library |
| **Containerization** | Docker, Docker Compose |
| **CI/CD** | GitHub Actions |

---

## 📁 Project Structure

---

## 🚀 Installation

### Prerequisites
- Python 3.9+
- Node.js 18+
- PostgreSQL 15+
- Git

### 1. Clone the Repository
```bash
git clone https://github.com/vishakha2121/ml-benchmark-automator.git
cd ml-benchmark-automator

# Create virtual environment
cd backend
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Setup database
createdb benchmark_db
alembic upgrade head

# Create .env file
cp .env.example .env
# Edit .env with your database credentials

cd ../frontend
npm install