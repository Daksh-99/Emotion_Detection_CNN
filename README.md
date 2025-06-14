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
| Happy   | ![img](https://storage.googleapis.com/kagglesdsdata/datasets/786787/1351797/test/happy/PrivateTest_10613684.jpg?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=databundle-worker-v2%40kaggle-161607.iam.gserviceaccount.com%2F20250614%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20250614T071357Z&X-Goog-Expires=345600&X-Goog-SignedHeaders=host&X-Goog-Signature=5061716744bc36be7f4f928dcf1cf02fd7684bb23fecf51a86d4fd6c83930c8284dd70fc7ad9abd3babe9cee1a11a4e59319d560d73b057113a00a89aa0cc4e1f654d87917cc6d28f951fee25363b8dcd71f5dacb3f0ab4b3a7d4804adcc00a0b1f396c64733148fc55b5fb8b8f302760e076d51947de79dfa2d1b248c30a2403f453289392568431e947e18f89a7dac110ebe9581dfb34c1da5548c4d4d63059963a2017d4df7fb3a5b46ecd9dd30321fcd8bc1256299f6b8f0b3e439979736772ffc970325ee67cd9a8f92bea88f0119c53f06158d6702fef8371490e7fa51d77bdaea1a49b0626a5080ba568779e89718e830008b18018420f2e0c784685e) |
| Sad     | ![img](https://storage.googleapis.com/kagglesdsdata/datasets/786787/1351797/test/sad/PrivateTest_13437169.jpg?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=databundle-worker-v2%40kaggle-161607.iam.gserviceaccount.com%2F20250614%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20250614T071433Z&X-Goog-Expires=345600&X-Goog-SignedHeaders=host&X-Goog-Signature=cff3f0c55a02a63167b6bf2355502acea7708574f209918b03391671a574d655ce5c26424e8dabd92b39a3a913f3810e3e6abf190bd3eea3b6f0146b2358b5b1523b565e27b39ef460e47abafb3c8dbe8ffdde38fcaddd99f57f3a04b30a8a6b662a364a8afe5ec1c4c0d49ece946edb16f1a4e1cb9b7d39859b8647827c69ba0f30886013d7b6d0088f516c790a6563f9ead5a8c2b512f6a6fd8b078d864e018794adca62fe89fd97cb32424f4b398083a0265acbecf3417f77853609df5136e29c6b81a4ef7a1f84c06fbe87a7c3bca73bf1695321fe9523d15885db0f644d4c1750088fba863091adce54864c059d8651c48d5be865df78d1c901c4fa5ac1) |

## Usage
Clone the repo:
```bash
git clone https://github.com/yourusername/emotion-detection-cnn.git
cd emotion-detection-cnn
pip install -r requirements.txt
Open notebook in Jupyter or Colab
