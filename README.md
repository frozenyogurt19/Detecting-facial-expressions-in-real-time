# 📷🎭 Detecting-facial-expressions-in-real-time :

🎭 This project is a  basic  real-time face expression detector using CNN model and OpenCV.
-It distingushed between 7 main emotion : Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral

---
✨ What makes this project special to me is  learning integarte machine learning ,data scienec with computer vision to create
and intractive an easy to understand system by almost any age group. 

---
## 📍Flow of work:
1. Webcam captures data
2. face is detected (using OpenCV)
3. CNN model makes predictions ( model trained on open src data : FER2013 )
4. Predicted emotion is displayed on web cam in resl-time!
   
---
📂 Project Structure
```bash
emotion_detector/
│
├── app.ipynb                # Complete pipeline: data prep, training, testing, webcam demo
├── main.py                  # Runs real-time emotion detection via webcam
├── expression_model.h5      # Trained CNN model (legacy format)
├── expression_model.keras   # Trained CNN model (modern format)
├── requirements.txt         # All required Python libraries
├── README.md                # You're reading it!
```


---

⚠️ NOTE: The raw image dataset (FER2013) is not included due to size. You can download it from Kaggle.

<br>

❓ How to run :

Clone the repo :
git clone https://github.com/frozenyogurt19/Detecting-facial-expressions-in-real-time-.git

cd Detecting-facial-expressions-in-real-time-


Install dependencies :
pip install -r requirements.txt

Run the webcam demo :
python main.ipynb 

OR open jupyter notebook app.ipynb ,  to train and test manually.

---

