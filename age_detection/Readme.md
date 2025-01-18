# Age Detection Using UTKFace Dataset

## 📊 Dataset

This project utilizes the **UTKFace Dataset** for predicting a person's age based on facial images.

- **Dataset Source:** [UTKFace Dataset on Kaggle](https://www.kaggle.com/datasets/jangedoo/utkface-new)
- **Content:** Over 20,000 facial images labeled with **Age**, **Gender**, and **Ethnicity**.
- **Format:** Image files named as `age_gender_race_date.jpg` (e.g., `25_0_2_20170109150557335.jpg`)

## 📥 Dataset Download

To download the dataset automatically, run the following code:

```python
import kagglehub

# Download the latest version of the UTKFace dataset
path = kagglehub.dataset_download("jangedoo/utkface-new")

print("Path to dataset files:", path)
```

**Install Required Package:**
```bash
pip install kagglehub
```

## 📂 Project Directory Structure

```
project-root/
├── data/
│   └── utkface-new/
│       ├── 25_0_2_20170109150557335.jpg
│       ├── 30_1_3_20170109142408075.jpg
│       └── ...
├── main.py
└── README.md
```

## 🔍 Dataset Loading Example

```python
import os
from PIL import Image

# Path to the downloaded dataset
dataset_path = os.path.join(path, 'utkface-new')

# Load and display a sample image
sample_image = os.path.join(dataset_path, '25_0_2_20170109150557335.jpg')
image = Image.open(sample_image)
image.show()
```

## 🚀 Project Overview

This project involves training a machine learning model to predict age from facial images. The model leverages deep learning techniques for accurate predictions.

### Key Features:
- Image preprocessing and augmentation.
- Age prediction using Convolutional Neural Networks (CNN).
- Visualization of predictions.


## 📊 Results

The model achieves high accuracy in predicting the age of individuals based on facial images. Below is a sample output:

```
Predicted Age: 24
Actual Age: 25
```



