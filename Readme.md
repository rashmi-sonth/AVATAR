# 🚗🔧 AVATAR – Autonomous Vehicle AI-powered Traffic And Resource Optimization

## 🚀 Project Overview

This project focuses on predicting **resource allocation** for autonomous vehicles based on key network parameters such as **signal strength, latency, and resource demand**. We employ various **deep learning models**, including:

- **CNN-LSTM Hybrid Model**
- **Transformer for Time-Series (TST)**
- **Temporal Fusion Transformer (TFT)**

We compare models based on **Mean Absolute Error (MAE), Mean Squared Error (MSE), Model Size, and Inference Time.**

---

## 📊 Dataset & Code Structure

- **`Quality of Service 5G.csv`** → The dataset used for training and evaluation.
- **`code.ipynb`** → The Jupyter Notebook containing all model training and evaluation code. Three deep learning models (**CNN-LSTM, TST, and TFT**) have been implemented, and a comparison is conducted in terms of **MAE, MSE, Model Size, and Inference Time**.
- **`models/`** → Folder containing trained deep learning models.

The dataset consists of **400 network traffic records** with the following attributes:

| Column               | Description                                   |
| -------------------- | --------------------------------------------- |
| Timestamp            | Time of network event                         |
| User\_ID             | Unique identifier for users                   |
| Application\_Type    | Type of application (Video, Streaming, etc.)  |
| Signal\_Strength     | Network signal strength in dBm                |
| Latency              | Network latency in ms                         |
| Required\_Bandwidth  | Bandwidth required by application (Mbps/Kbps) |
| Allocated\_Bandwidth | Bandwidth allocated by network (Mbps/Kbps)    |
| Resource\_Allocation | Percentage of allocated network resources     |

---

## ⚡ Installation & Usage

### **1. Install Dependencies**

```bash
pip install numpy pandas matplotlib scikit-learn statsmodels tensorflow torch
```

### **2. Execute the Jupyter Notebook**

```bash
jupyter notebook code.ipynb
```

## 📩 Contact

For any queries or contributions, feel free to reach out to the project maintainer.
