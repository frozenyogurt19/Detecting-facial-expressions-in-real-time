# 🎭🎭 Detecting-facial-expressions-in-real-time :

This project is a  basic  real-time face expression detector using CNN model and OpenCV.
-It distingushed between 7 main emotion : Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral


##📍Flow of work:
1. Webcam captures data
2. face is detected (using OpenCV)
3. CNN model makes predictions ( model trained on open src data : FER2013 )
4. Predicted emotion is displayed on web cam in resl-time!


## 📂 Project Structure

```bash
emotion_detector/
│
├── app.ipynb                  # Model training and testing notebook
├── expression_model.h5        # Trained CNN model (old format)
├── expression_model.keras        # Trained CNN model (new format)
├── X_train.npy / y_train.npy  # Preprocessed train data
├── X_test.npy / y_test.npy    # Preprocessed test data
├── requirements.txt           # List of required packages
├── README.md                  # This file

##⚠️ The raw image dataset (FER2013) is not included due to size. You can download it from Kaggle.


## ❓ How to run :
