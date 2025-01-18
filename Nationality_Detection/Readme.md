# 📊 Datasets for Face, Emotion, Color, and Nationality Detection

## 1️⃣ Face Detection Dataset

**Dataset:** [UTKFace Dataset](https://www.kaggle.com/datasets/jangedoo/utkface-new)  
**Description:** A large-scale face dataset with over 20,000 images labeled with age, gender, and ethnicity. It is widely used for facial recognition and age estimation tasks.  
**Format:** `age_gender_race_date.jpg` (e.g., `25_0_2_20170109150557335.jpg`)

---

## 2️⃣ Emotion Detection Dataset

**Dataset:** [FER-2013 Emotion Dataset](https://www.kaggle.com/datasets/msambare/fer2013)  
**Description:** A dataset containing grayscale images of human faces labeled with seven different emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.  
**Format:** 48x48 pixel grayscale images in CSV format.

---

## 3️⃣ Color Detection Dataset

**Dataset:** [RGB to Color Name Dataset](https://www.kaggle.com/datasets/khushipathak/color-detection-dataset)  
**Description:** A dataset designed for detecting and classifying colors based on RGB values, mapping them to color names.  
**Format:** CSV file containing RGB values and corresponding color names.

---

## 4️⃣ Nationality Detection Dataset

**Dataset:** [World Faces Dataset](https://www.kaggle.com/datasets/ashwingupta3012/face-dataset)  
**Description:** A comprehensive face dataset categorized by different nationalities for use in nationality prediction models.  
**Format:** Images sorted into folders based on nationality labels.

---

## 📥 How to Download Datasets

Install Kaggle API to download datasets easily:

```bash
pip install kagglehub
```

### Example Code to Download a Dataset:

```python
import kagglehub

# Download the UTKFace dataset
path = kagglehub.dataset_download("jangedoo/utkface-new")
print("Dataset downloaded at:", path)
```

---

## 🔗 Useful Links

- [Kaggle API Documentation](https://www.kaggle.com/docs/api)
- [Kaggle Datasets](https://www.kaggle.com/datasets)

---

**Developed by Sruthi**
