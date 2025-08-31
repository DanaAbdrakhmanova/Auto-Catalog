# 🚗 Car Catalog (Streamlit + ngrok)

A **Streamlit** web app for exploring and filtering cars by make, model, and year, with recommendations for similar vehicles. Works in Google Colab with **ngrok** for public access.  

## 📌 Features

- Filter cars by:
  - **Make** (`make`)
  - **Model** (`model`)
  - **Year** (`year`)
- View filtered cars with details:
  - **Fuel type** (`fuelType`)
  - **Drive type** (`drive`)
- Get recommendations for the same model from other brands.
- Easy online deployment via **ngrok** (perfect for Colab).  

## ⚙️ Installation & Usage

### 1. Install dependencies
```bash
pip install streamlit pyngrok pandas
