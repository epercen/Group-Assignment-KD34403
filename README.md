
```markdown
# 🌱 Plant Disease Detection Using Deep Learning

This is a Flask-based web application that allows users to detect plant diseases by uploading an image of a leaf. It uses a Convolutional Neural Network (CNN) model to predict the disease and provides useful prevention steps and supplement suggestions.

Video Showcase : https://youtu.be/8OS1OxrShww

---

## 📁 Project Structure

```'

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
git clone https://github.com/epercen/Group-Assignment-KD34403.git
cd Group-Assignment-KD34403

Then Download the model file here = https://drive.google.com/file/d/11OpQKbNkJ_Ncny2Q7n7vHuK7Y8_E5XjJ/view?usp=sharing

````

### 2. 🐍 Create and Activate a Virtual Environment



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


