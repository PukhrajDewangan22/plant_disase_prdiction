
# 🌿 Paudha Rakshak– Plant Disease Detection Using AI

**Paudha Rakshak** is a responsive web-based application built using **Flask** and **Machine Learning** to detect plant diseases from images. Users can **upload plant leaf images** or **capture photos using the device’s rear camera**. Based on the image, the app detects the disease and provides:

- 🌱 Disease name  
- 💊 Precautionary measures  
- 🌾 Recommended fertilizers and supplements  

Additionally, the platform allows users to **borrow essential gardening items**, such as **fertilizers, supplements, and other plant-care equipment**, making it a complete tool for plant health and management.

---

## 📸 Features

- Detect plant diseases using a trained ML model
- Upload images or capture using the rear camera
- Get precautions and treatment recommendations
- Borrow plant essentials like fertilizers and supplements
- Clean, responsive design for all screen sizes
- Backend powered by Flask; image processing with Pillow; data lookup with Pandas

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **ML**: scikit-learn / TensorFlow 
- **Libraries Used**:
  - `Flask` – Web application framework
  - `Pandas` – For data lookup and mapping
  - `Pillow` – For image preprocessing
  - `scikit-learn` – For model prediction

---

## 📁 Project Structure

```

Paudha-Rakshak/
│
├── static/                 # CSS, JavaScript files
├── templates/              # HTML files (Jinja templates)
├── model/                  # Trained ML model
├── uploads/                # Uploaded plant images
├── app.py                  # Main Flask application
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation

````

---

## 🧪 How to Access and Run the Project

### 🔧 Installation & Setup Instructions

1. **Clone the Repository**
```lookml
```bash
git clone https://github.com/yourusername/Paudha-Rakshak.git
cd Paudha-Rakshak
```

2. **Create and Activate Virtual Environment**

* **Windows**

```bash
python -m venv env
env\Scripts\activate
```

* **macOS/Linux**

```bash
python3 -m venv env
source env/bin/activate
```

3. **Add `requirements.txt` Manually**

Create a file named `requirements.txt` inside your project folder (`Paudha-Rakshak/`) and copy the following:

```txt
Flask
pandas
Pillow
scikit-learn
```

> ✅ *Add any other packages you use in your app.*

4. **Install Dependencies**

```bash
pip install -r requirements.txt
```

5. **File Setup**


* Go to the `FlaskApp` folder.
* Download the pre-trained model file [`plant_disease_model_1.pt`](https://drive.google.com/drive/folders/1ewJWAiduGuld_9oGSrTuLumg9y62qS6A).
* Place the downloaded file inside the `FlaskApp` directory.


6. **Run the Flask App**

```bash
python app.py
```

7. **Open the Application in Browser**

Navigate to:
👉 `http://127.0.0.1:5000`

---

## 🧾 Tasks Performed

* Built user interface using HTML, CSS, and JavaScript
* Integrated device rear-camera functionality
* Used Pillow to handle uploaded and captured images
* Applied a machine learning model to classify plant diseases
* Used Pandas to fetch and display treatment and fertilizer info
* Added feature to borrow essential plant care equipment

---

## ✅ Sample Output

---

### 💻 Output Web Interface

#### 🏠 Homepage

![Homepage](https://github.com/PukhrajDewangan22/Paudha_Rakshak/blob/main/output_images/Screenshot%20\(40\).png)

#### 🔐 Login Page

![Login Page](https://github.com/PukhrajDewangan22/Paudha_Rakshak/blob/main/output_images/Screenshot%20\(45\).png)

#### 🤖 Paudha Rakshak AI Engine

![AI Engine](https://github.com/PukhrajDewangan22/Paudha_Rakshak/blob/main/output_images/Screenshot%20\(41\).png)

#### 🌿 Paudha Essentials

![Paudha Essentials](https://github.com/PukhrajDewangan22/Paudha_Rakshak/blob/main/output_images/Screenshot%20\(42\).png)

#### 📬 Get in Touch

![Get in Touch](https://github.com/PukhrajDewangan22/Paudha_Rakshak/blob/main/output_images/Screenshot%20\(44\).png)

---

## 👨‍💻 Authors

* **Pukhraj Dewangan**
* **Shasank Baxi**

---

## 📃 License

This project is licensed under the **MIT License**.


