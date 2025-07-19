# 🧍‍♂️ Pose Classifier using MediaPipe and Scikit-Learn

This project is a pose classification system that uses MediaPipe to extract keypoints and Scikit-Learn to classify different martial arts poses such as **jab**, **cross**, and **hook**.

## 🔧 Technologies Used
- Python
- MediaPipe
- NumPy
- Scikit-learn
- OpenCV (optional for visualization)

## 📂 Project Structure

AICombatCoach/
|---models/
|---data/
| |---cross/
| |---guard/
| |---jab/
|---notebooks/
| |---.ipynb_checkpoints/
| |---01_data_collection
| |---pose_classifier
| |---X.npy
| |---y.npy
|---utils/
|---requirements.txt



## ✅ Features
- Collects pose data using MediaPipe Holistic model.
- Trains a pose classifier using RandomForestClassifier.
- Predicts poses in real-time using webcam.
- Modular and easy to extend for new poses.

## 🛠️ Requirements

Install required libraries:
```bash
pip install opencv-python mediapipe scikit-learn joblib numpy


##🏃 Usage
1. Collect Pose Data
Run the script and press keys 0, 1, 2 for different poses (jab, cross, guard).
(python collect_data.py)
2. Train Model
(python train_model.py)
3. Predict in Real-Time
(python predict_pose.py)



💡 Future Ideas
Add more pose types (kick, dodge, etc.)

Use LSTM for temporal classification

Deploy as a web app

👨‍💻 Author
Suresh-source07
GitHub

Let me know if you'd like a logo, requirements.txt, or license added too.

