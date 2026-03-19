## 🔄 Workflow

### 📌 Data Processing & Input
- Capture real-time video using webcam  
- Detect colored object (green bottle cap in this case) using OpenCV  
- Track motion to simulate handwriting in air  
- Convert tracked path into image format  
---
### 🧠 Models Used
- OpenCV for real-time tracking and preprocessing
- Multilayer Perceptron (MLP) for alphabet classification  

> The system recognizes English alphabets written in air and predicts them in real time.
---
## 🚀 How to Run

1. Run `MLP Model.py` to build and train the MLP model to recognize alphabets 
2. Run `Handwriting_recognizer.py` to start real-time tracking
3. Use a green bottle cap in front of the webcam  
4. Start writing in the air in front of the webcam to get predictions  

> ⚠️ NOTE:  
> - The system currently takes input in real time using a webcam  
> - You can modify it to accept a preloaded video as input if needed  
---
## 🛠️ Core Packages Used

- OpenCV
- Keras
- NumPy  
- Pandas    
---
