# Sign Language Action Recognition 🤟

A real-time sign and gesture recognition system using **Mediapipe keypoints** and an **LSTM neural network** trained in TensorFlow.

---

## 🧠 Overview
This notebook trains and tests an action recognition model that can classify sign language gestures using sequential keypoint data.  
It’s designed for both recorded datasets and live webcam input.

## 📁 Repository Structure
Sign-Language-Detection/
├─ ActionRecognition.ipynb # Main notebook (training + testing)
├─ requirements.txt # Dependencies list
└─ Logs/
└─ train/ # Training logs and metrics


## ⚙️ Setup & Usage
1. **Clone this repo**
   ```bash
   git clone https://github.com/Rohan1x/Sign-Language-Detection.git
   cd Sign-Language-Detection

Create and activate a virtual environment

python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate


Install dependencies

pip install -r requirements.txt


Launch Jupyter

jupyter lab   # or jupyter notebook


Then open ActionRecognition.ipynb and run each cell sequentially.



🧩 Features

Extracts pose/hand/face keypoints with Mediapipe Holistic

Preprocesses keypoint sequences for model input

Trains an LSTM model in TensorFlow/Keras

Evaluates accuracy and confusion matrix

Optional real-time webcam demo via OpenCV

📊 Results

Validation accuracy ≈ 93%

Low latency (<0.2 s per frame)

Logs automatically saved under Logs/train/

🧰 Tools Used

Python · TensorFlow · Keras · Mediapipe · OpenCV · NumPy · Pandas · Matplotlib

👤 Author

Rohan Domenguez
