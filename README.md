## ✌️ASL Hand Gesture Recognition with PyTorch CNN

**Static image classifier for 10 American Sign Language (ASL) letters** (A, B, C, D, E, F, I, L, O, V) using a custom Convolutional Neural Network.

This project demonstrates a complete machine learning workflow:
- Data exploration and preparation
- Robust training with data augmentation
- Validation monitoring
- Evaluation with confusion matrix and test predictions
- Model saving for future inference

Future extension: Add live webcam inference for real-time fingerspelling.

### Project Highlights

- **Dataset**: Kaggle Sign Language Gesture Images (subset of 10 classes)
- **Model**: Lightweight CNN with 3 convolutional blocks + dropout
- **Input**: 64×64 grayscale images
- **Key Techniques**:
  - Data augmentation (rotation, flip, brightness, shift) for real-world robustness
  - Train/validation/test split
  - Validation monitoring during training
  - Confusion matrix & test accuracy evaluation
  - Visual prediction results (correct vs wrong)
- **Output**: Trained PyTorch model ready for inference


## ⚙️ Setup & Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/kduffuor/ASL-Hand-Gesture-Recognition-CNN.git
   cd asl-hand-gesture-recognition-cnn

2. **Install dependencies:**
   ```bash
   pip install torch torchvision opencv-python matplotlib seaborn scikit-learn pillow

3. Download the dataset:

- Kaggle Dataset: [Sign Language Gesture Images Dataset](https://www.kaggle.com/datasets/ahmedkhanak1995/sign-language-gesture-images-dataset)
- Unzip and place the folder as Gesture Image Data in the project root

4. **Run the notebook:**
   ```bash
   jupyter notebook ASL_Gesture.ipynb
