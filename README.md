# Emotion recognition

# Facial Emotion Recognition

This project detects human emotions (Happy, Sad, Surprised) from facial landmarks using a **Random Forest Classifier**.  
It consists of three main scripts: data preparation, model training, and real-time testing.

---

## 📂 Project Structure
- `prepare_data.py` – Extracts face landmarks from images in `./data/` and saves them into `data.txt`.
- `train_model.py` – Trains a Random Forest classifier on the prepared dataset and saves the model.
- `test_model.py` – Loads the trained model and performs real-time emotion detection via webcam.
- `utils.py` – Contains helper functions (e.g., `get_face_landmarks`) for face landmark extraction.

---

## 🚀 Usage
1. **Prepare Data**
   ```bash
   python prepare_data.py
