🧠 Face Recognition Project

A complete face recognition system built using Python, OpenCV, and the face_recognition library. This project supports real-time face detection, face encoding, training, and recognition. It can be extended for attendance systems, security applications, and smart access control.

📌 Features

✔️ Real-time face detection using OpenCV

✔️ Face encoding and recognition

✔️ Add and train multiple users

✔️ Automatic marking of recognized faces

✔️ Easy to extend for attendance or security use cases

✔️ Clean and modular Python code

📂 Project Structure
face_recognition_project/
│── dataset/                # Store face images of known persons
│── encodings/              # Saved face encodings
│── models/                 # ML models (if used)
│── main.py                 # Entry point for real-time detection
│── train.py                # Script to train face encodings
│── requirements.txt        # Project dependencies
│── README.md               # Documentation


🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/your-username/face_recognition_project.git
cd face_recognition_project

2️⃣ Install dependencies

Make sure you have Python 3.7+ installed.

pip install -r requirements.txt

3️⃣ Add training images

Place images in the dataset/ folder:

dataset/
│── person1/
│     ├── img1.jpg
│     ├── img2.jpg
│── person2/
      ├── img1.jpg
      ├── img2.jpg

4️⃣ Train face encodings
python train.py

5️⃣ Run real-time face recognition
python main.py

🖥️ Requirements

Python 3.7+

OpenCV

dlib (optional)

face_recognition

numpy

imutils

📸 How It Works

The system detects faces using OpenCV

Extracts face encodings using the face_recognition library

Compares encodings with trained faces

Displays the recognized person’s name on the screen

🛠️ Technologies Used

Python

OpenCV

face_recognition (dlib + HOG/CNN models)

NumPy

🙌 Future Improvements

Add GUI dashboard

Implement attendance system

Store results in database

Deploy on Raspberry Pi

Add door lock IoT integration
