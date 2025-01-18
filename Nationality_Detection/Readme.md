# 📊 Datasets for Face, Emotion, Color, and Nationality Detection

## 1️⃣ Face & Nationality Detection Dataset

**Dataset:** [UTKFace Dataset](https://www.kaggle.com/datasets/jangedoo/utkface-new)  
**Description:** A large-scale face dataset with over 20,000 images labeled with age, gender, and ethnicity. It is widely used for facial recognition, age estimation, and nationality prediction tasks.  
**Format:** `age_gender_race_date.jpg` (e.g., `25_0_2_20170109150557335.jpg`)

---

## 2️⃣ Emotion Detection Dataset

**Dataset:** [FER-2013 Emotion Dataset](https://www.kaggle.com/datasets/msambare/fer2013)  
**Description:** A dataset containing grayscale images of human faces labeled with seven different emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.  
**Format:** 48x48 pixel grayscale images in CSV format.

---

## 3️⃣ Color Detection Dataset

**Dataset:** [Color Dataset for Color Recognition](https://www.kaggle.com/datasets/adikurniawan/color-dataset-for-color-recognition)  
**Description:** A dataset designed for detecting and classifying colors based on RGB values, mapping them to color names.  
**Format:** CSV file containing RGB values and corresponding color names.

---

## 📥 How to Download Datasets

Install Kaggle API to download datasets easily:

```bash
pip install kagglehub
```

### Example Code to Download a Dataset:

```python
import kagglehub

# Download the UTKFace dataset for face and nationality detection
path = kagglehub.dataset_download("jangedoo/utkface-new")
print("UTKFace Dataset downloaded at:", path)

# Download the Color dataset for color detection
path = kagglehub.dataset_download("adikurniawan/color-dataset-for-color-recognition")
print("Color Dataset downloaded at:", path)
```

---

## 🔗 Useful Links

- [Kaggle API Documentation](https://www.kaggle.com/docs/api)
- [Kaggle Datasets](https://www.kaggle.com/datasets)

---

**Developed by Sruthi**
