# Facial Expression Detector

A real-time facial expression detection system built with OpenCV and a pre-trained deep learning model.

## What it does
Detects faces through a webcam feed and classifies the expression into emotions like happy, sad, angry, surprised, neutral, etc. in real time.

## Tech Stack
- Python
- OpenCV (for face detection via Haar Cascade)
- Pre-trained model: Xception architecture trained on FER-2013 dataset

## How to run

1. Clone the repo
```bash
   git clone https://github.com/adithyakn/Facial-expression-detector.git
   cd Facial-expression-detector
```

2. Create and activate a virtual environment
```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
   pip install opencv-python tensorflow numpy
```

4. Run the program
```bash
   python main.py
```

## Dataset
Model trained on the [FER-2013 dataset](https://www.kaggle.com/datasets/msambare/fer2013) — 35,000+ facial images across 7 emotion categories.

## Notes
- Requires a webcam
- Run inside a virtual environment for best results
