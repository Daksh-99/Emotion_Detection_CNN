# Emotion Detection using CNN

## Overview
A Convolutional Neural Network (CNN) based project to detect human emotions from facial images using Python and TensorFlow.

## Dataset
- FER-2013 Emotion Dataset
- Available on Kaggle: https://www.kaggle.com/datasets/msambare/fer2013

## Tech Stack
- Python
- TensorFlow & Keras
- OpenCV
- Matplotlib
- Scikit-learn

## Project Flow
1. Load & Preprocess Data
2. Build CNN Architecture
3. Train & Evaluate the Model
4. Visualize Accuracy & Loss
5. Predict on Custom Images

## Results
Achieved ~63% accuracy on validation data.

### Sample Output
| Emotion | Example |
|---------|---------|
| Happy   | ![img](outputs/happy.png) |
| Sad     | ![img](outputs/sad.png) |

## Usage
Clone the repo:
```bash
git clone https://github.com/yourusername/emotion-detection-cnn.git
cd emotion-detection-cnn
pip install -r requirements.txt
Open notebook in Jupyter or Colab
