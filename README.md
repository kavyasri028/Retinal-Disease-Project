# Retinal Disease Detection Project

This project is a deep learning web application built using Flask for detecting retinal diseases using Convolutional Neural Networks (CNN).

## 🔍 Features
- Upload retinal images and detect disease type
- Pre-trained CNN models (`cnn.h5`, `mobile.h5`, `xec.h5`)
- Simple user interface using HTML/CSS and Flask

---

## 🧠 Tech Stack
- Python 3.10
- Flask
- TensorFlow / Keras
- OpenCV
- HTML/CSS/Bootstrap

---

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/kavyasri028/Retinal-Disease-Project.git
cd Retinal-Disease-Project
```

### 2. Set up a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install the requirements
```bash
pip install -r requirements.txt
```

### 4. Download the Model Files
> Due to GitHub file size limits, model files are managed using Git LFS. If not downloaded automatically, [download them here](https://drive.google.com/your-link) and place them in the project root:
- `cnn.h5`
- `mobile.h5`
- `xec.h5`

### 5. Run the App
```bash
python app.py
```

Open your browser and go to `http://127.0.0.1:5000`

---

## 📁 Project Structure
```
Retinal-Disease-Project/
├── app.py
├── cnn.h5
├── mobile.h5
├── xec.h5
├── templates/
├── static/
├── sample/
├── EyeNet-master/
├── README.md
├── .gitignore
└── requirements.txt
```

---

## 🙋‍♀️ Maintainer
- **Kavya Sri Inkollu**
  - GitHub: [@kavyasri028](https://github.com/kavyasri028)

---

## ✅ TODO
- [ ] Add dataset download link
- [ ] Improve frontend UI
- [ ] Add Docker support

---

## 📜 License
This project is licensed under the MIT License.
