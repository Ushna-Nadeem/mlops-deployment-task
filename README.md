# 🍪 Sweet or Savory Predictor – MLOps Deployment Task

A web application that uses a machine learning model to predict whether a food item is **sweet** or **savory** based on its ingredient quantities.

---

## 📌 Overview

This project includes:

* **🧠 Model Training:** Trains a classifier to predict food type using ingredients
* **⚙️ Flask API:** Serves predictions via a lightweight backend
* **🖥️ Frontend:** Simple HTML form for input and result display

---

## 📁 Project Structure

| File               | Description                                 |
| ------------------ | ------------------------------------------- |
| `app.py`           | Flask app that serves the prediction API    |
| `model.py`         | Trains and saves the machine learning model |
| `index.html`       | Web UI for entering ingredient data         |
| `requirements.txt` | Python dependencies                         |
| `.gitignore`       | Files to ignore in version control          |

---

## 🚀 How to Use

1. **Input Ingredients**

   * Enter ingredient quantities in grams (e.g., `100, 50, 5, 20` for flour, sugar, salt, butter)

2. **Click "Predict"**

   * Submits the data to the backend Flask server

3. **View Prediction**

   * The app displays either **Sweet** 🍬 or **Savory** 🧂 based on the input

---

## 🛠 Setup Instructions

```bash
# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```

Open your browser at **[http://localhost:5000](http://localhost:5000)** to use the app.
