# Fruit Recognition with CNN & VGG16

End-to-end image classification pipeline: **aHash-based duplicate filtering**, clean **train/val split**, **Keras CNN** and **VGG16 transfer learning** comparison, metrics, and activation map visualizations.

## Features
- ✅ aHash duplicate filtering → prevents data leakage (`clean_split/`)
- ✅ CNN baseline + VGG16 (frozen + optional fine-tune)
- ✅ EarlyStopping, ReduceLROnPlateau, ModelCheckpoint
- ✅ Confusion matrix, classification report, sample visualizations
- ✅ Reproducible with fixed seeds

## Dataset
- Kaggle: [Fruit Recognition](https://www.kaggle.com/datasets/sshikamaru/fruit-recognition)

## Notebook (Kaggle)

Projenin Kaggle üzerindeki notebook versiyonuna buradan ulaşabilirsiniz:  
👉 [CNN Image Classifier – Kaggle Notebook](https://www.kaggle.com/code/mehmettsaglam/cnn-img-classifier)

## Setup
```bash
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt


