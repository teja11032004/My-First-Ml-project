# 🔥 Forest Fire Weather Index (FWI) Prediction Web App

This project predicts the **Forest Fire Weather Index (FWI)** using environmental parameters such as **Temperature, Humidity, Wind Speed, and Rainfall**.  
It provides a risk level indicating how likely a forest fire is to occur under given weather conditions.

---

## 📘 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model & Prediction](#model--prediction)
- [Tech Stack](#tech-stack)
  

---

## 🌲 Overview

The **FWI Prediction App** is a machine learning–powered web application that:
- Takes weather-related input features
- Predicts the **Fire Weather Index (FWI)**
- Categorizes fire risk into levels such as *Low*, *Moderate*, *High*, *Very High*, and *Extreme*  

It uses a trained regression/classification model to assist environmental monitoring teams and forest officers in assessing wildfire risks more accurately.

---

## ✨ Features
- 🔹 **Interactive Web Interface** built with Streamlit  
- 🔹 **Welcome Page** with navigation to prediction page  
- 🔹 **FWI Prediction** using pre-trained ML model  
- 🔹 **Supports manual input or CSV upload** for bulk prediction  
- 🔹 **Visual analytics** for dataset insights  
- 🔹 Lightweight, fast, and user-friendly design

---

## 🧠 Dataset

The dataset contains daily meteorological observations and fire weather index data.

| Column | Description |
|:--------|:-------------|
| `Temperature` | Ambient temperature (°C) |
| `RH` | Relative Humidity (%) |
| `Ws` | Wind Speed (km/h) |
| `Rain` | Rainfall (mm) |
| `FFMC` | Fine Fuel Moisture Code |
| `DMC` | Duff Moisture Code |
| `DC` | Drought Code |
| `ISI` | Initial Spread Index |
| `BUI` | Buildup Index |
| `FWI` | Fire Weather Index (target variable) |
| `Classes` | Fire risk category label (Low, Moderate, etc.) |

---

## ⚙️ Installation

Follow these steps to set up and run the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/teja11032004/My-First-Ml-project
cd My-First_Ml-project
