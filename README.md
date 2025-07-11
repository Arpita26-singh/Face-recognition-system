# 👁️ Face Recognition System using Python

A real-time face recognition system built using Python, OpenCV, and machine learning. It detects and identifies human faces from images or live webcam input with high accuracy using face encodings.

---

## 🚀 Features

* Real-time face detection using webcam
* Face encoding and recognition using `face_recognition` library
* Dataset folder structure for known persons
* Statistical evaluation (Accuracy, Precision, F1-Score)
* Confusion matrix visualization
* Clean and modular code structure

---

## 💠 Technologies Used

* Python 3.x
* OpenCV (`cv2`)
* face\_recognition
* NumPy
* scikit-learn
* Matplotlib / Seaborn (for evaluation)

---

## 📁 Folder Structure

```
project/
├── dataset/
│   ├── Ravi/
│   │   ├── img1.jpg
│   │   └── img2.jpg
│   ├── Anjali/
│       ├── img1.jpg
│       └── img2.jpg
├── main.py
├── encode_faces.py
├── evaluate_model.py
├── README.md
```

---

## 🧪 How It Works

1. **Data Collection**: Store images in folders named after each person.
2. **Preprocessing**: Convert images to RGB and extract 128D face encodings.
3. **Model Training**: Use ML classifiers (KNN, SVM, Random Forest, etc.).
4. **Prediction**: Match unknown faces with known encodings in real-time.
5. **Evaluation**: Use metrics like accuracy, precision, F1-score & confusion matrix.

---

## 🧠 Future Scope

* Add liveness detection (eye-blink, 3D mask)
* Deploy on mobile or Raspberry Pi
* API integration with cloud databases
* Multi-factor authentication (OTP + Face)

---

## ⚠️ Limitations

* No liveness detection (can be tricked by photos)
* Sensitive to lighting and pose variations
* Resource intensive (better on systems with GPU)

---

## 📷 Demo

> *(Add screenshots or link to demo video here)*

---

## 👨‍💻 Author

**\[Your Name]**
B.Tech CSE | Arka Jain University
Aspiring Data Analyst | IoT Enthusiast | GDSC Member

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
