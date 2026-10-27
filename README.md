# Wild Animal Detection System 🦁

An AI-based system to detect wild animals in real-time and prevent human-wildlife conflict.

### 👨‍💻 Developed by: Dudekula Rohin Baba

### 🔧 Tech Stack
- Python, OpenCV, YOLOv8, Deep Learning

### 📂 Training
The trained model best.pt will be saved under:
runs/detect/animal_detector/weights/best.pt

### 💻 Real-Time Detection (VS Code)
from ultralytics import YOLO
model = YOLO('best.pt')
model.predict(source=0, show=True) # 0 for webcam

### 🎯 Results
Achieved 90%+ detection accuracy for multiple wild animal species including Tiger, Elephant, Bear and Leopard in diverse environments.

### 🔗 Connect
GitHub: github.com/dudekularohinbaba22


📊 Results

The trained YOLOv8 model achieves high detection accuracy for multiple wild animal species in diverse environment.


