
```markdown
# 🌱 Plant Disease Detection Using Deep Learning

This is a Flask-based web application that allows users to detect plant diseases by uploading an image of a leaf. It uses a Convolutional Neural Network (CNN) model to predict the disease and provides useful prevention steps and supplement suggestions.

---

## 📁 Project Structure

```

├── app.py                        # Flask backend script
├── CNN.py                        # CNN model definition
├── static/                       # Static assets (images, CSS, uploads)
│   └── uploads/
├── templates/                    # HTML templates for the web pages
├── requirements.txt              # List of dependencies
├── disease\_info.csv              # Information about each plant disease
├── supplement\_info.csv           # Supplement details for each disease

````

---

## 🚀 How to Download & Run the Project Locally

Follow the steps below to set up and run the application on your machine:

### 1. 🔄 Clone the Repository

```bash
git clone https://github.com/your-username/Plant-Disease-Detection.git
cd Plant-Disease-Detection
````

### 2. 🐍 Create and Activate a Virtual Environment

#### On macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

#### On Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. 📦 Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 4. 🧠 Download the Trained Model

Make sure the trained model file `plant_disease_model_1_latest.pt` is in the root project directory. If it’s not included, request it from the project owner or original source.

### 5. ▶️ Run the Flask App

```bash
python app.py
```

Open your browser and go to `http://127.0.0.1:5000` to access the app.

---

## 💻 Recommended IDE

We recommend using **Visual Studio Code (VS Code)** for editing and running this project because of its excellent Python and Flask support.

---


