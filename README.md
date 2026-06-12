# 🦴 Bone Fracture Detection System

A desktop application that uses Machine Learning and Computer Vision techniques to detect bone fractures from X-ray images. The application provides an intuitive graphical interface built with CustomTkinter, allowing users to upload X-ray images, classify bone types, detect fractures, and save prediction results.

---

## 📌 Features

* Upload X-ray images for analysis
* Automatic bone fracture detection
* Bone type classification
* User-friendly GUI using CustomTkinter
* Display prediction results instantly
* Save prediction results as screenshots
* Information window with usage guidelines

---

## 🖥️ User Interface

The application provides:

### Upload Image

Users can select an X-ray image from their system.

### Predict

The system:

1. Identifies the bone type.
2. Detects whether the bone is fractured or normal.
3. Displays the prediction result.

### Save Result

Users can save the displayed prediction result as an image.

### Information Window

Displays instructions and guidelines for using the application.

---

## 📂 Project Structure

```text
Bone-Fracture-Detection/
│
├── images/
│   ├── info.png
│   ├── Question_Mark.jpg
│   └── rules.jpeg
│
├── test/
│   └── Wrist/
│
├── PredictResults/
│
├── predictions.py
├── main.py
├── requirements.txt
└── README.md
```

---

## 🛠️ Technologies Used

* Python
* CustomTkinter
* Tkinter
* Pillow (PIL)
* PyAutoGUI
* PyGetWindow
* Machine Learning
* Computer Vision

---

## 📦 Required Libraries

Install dependencies using:

```bash
pip install customtkinter
pip install pillow
pip install pyautogui
pip install pygetwindow
```

Or install from requirements file:

```bash
pip install -r requirements.txt
```

---

## 🚀 Running the Application

Clone the repository:

```bash
git clone https://github.com/your-username/Bone-Fracture-Detection.git
```

Navigate to the project directory:

```bash
cd Bone-Fracture-Detection
```

Run the application:

```bash
python main.py
```

---

## 🔍 How It Works

1. Upload an X-ray image.
2. Click **Predict**.
3. The model identifies:

   * Bone type
   * Fracture status
4. Results are displayed on the screen.
5. Click **Save Result** to store the prediction output.

---

## 📊 Output

The system classifies the image into one of the following categories:

### Fractured

* Displays:

  ```
  Result: Fractured
  ```
* Highlighted in Red.

### Normal

* Displays:

  ```
  Result: Normal
  ```
* Highlighted in Green.

Additionally, the detected bone type is displayed.

---

## 🎯 Future Improvements

* Support for additional bone categories
* Confidence score display
* Grad-CAM visualization for explainability
* Multi-fracture classification
* Cloud deployment
* Web-based application version

---

## 👨‍💻 Author

**Anirudh Chenna**

CMR College of Engineering & Technology

Artificial Intelligence & Machine Learning

---

## 📄 License

This project is developed for educational and research purposes.
