# 🐱🐶 Cats vs Dogs Image Classification

### My First Machine Learning Project | Google Teachable Machine

This is my first image classification project, built using **Google Teachable Machine**. I trained a machine learning model to recognize whether an uploaded image shows a **cat** or a **dog**.

The training images were sourced from a publicly available Kaggle dataset. After training, I tested the model using separate example images in Teachable Machine's preview interface.

## 📸 Project Screenshots

### 1. Model Training

![Cats and Dogs model training in Google Teachable Machine](images/Capture.PNG)

### 2. Cat Prediction

![Model correctly predicting a cat image](images/For%20Cats.PNG)

The model predicted **Cat** with **100% displayed confidence** for this test image.

### 3. Dog Prediction

![Model correctly predicting a dog image](images/For%20Dog.PNG)

The model predicted **Dog** with **100% displayed confidence** for this test image.

> **Note:** These screenshots show predictions on two example images. A 100% confidence score on an individual prediction does not mean the model has 100% accuracy on unseen data.

## 🎯 Project Objective

Build a beginner-friendly image classification model that can distinguish between cats and dogs using example images, without writing model-training code.

## 📊 Dataset

**Source:** [Cats and Dogs Image Classification — Kaggle, by samuelcortinhas](https://www.kaggle.com/datasets/samuelcortinhas/cats-and-dogs-image-classification)

| Class | Images used for training |
| --- | ---: |
| Cats | 279 |
| Dogs | 278 |
| **Total** | **557** |

The counts above are the images shown in the Teachable Machine training interface, not necessarily the full Kaggle dataset size.

## 🛠️ Tools and Technologies

- **Google Teachable Machine** — no-code image model training and prediction
- **Kaggle** — image dataset source
- **Web browser** — training and testing interface
- **Image classification / machine learning** — project domain

## ⚙️ How I Built the Model

1. Opened [Google Teachable Machine](https://teachablemachine.withgoogle.com/).
2. Selected **Get Started → Image Project → Standard Image Model**.
3. Created two classes: **Cats** and **Dogs**.
4. Downloaded the cat and dog image dataset from Kaggle.
5. Uploaded **279 cat images** and **278 dog images** into the corresponding classes.
6. Clicked **Train Model** and waited for training to finish.
7. Uploaded test images in the **Preview** panel to see the predicted class and confidence score.

## 🧪 Example Results

| Test image | Predicted class | Displayed confidence |
| --- | --- | ---: |
| Cat | Cats | 100% |
| Dog | Dogs | 100% |

These are demonstration results only. **Overall accuracy, precision, recall, F1-score, and performance on a held-out test set have not been measured or reported here.**

## 🚀 How to Reproduce

1. Download the dataset from the Kaggle link above.
2. Visit [Teachable Machine](https://teachablemachine.withgoogle.com/).
3. Start a standard image project with two classes, Cats and Dogs.
4. Upload labeled images to each class.
5. Train the model and try new images in the Preview panel.
6. Optionally use **Export Model** to download the trained model for use in another application.

> This repository documents the project with screenshots. It does **not** include an exported trained model unless model files are added separately.

## 📁 Repository Structure

```text
cats-dogs-image-classification/
├── README.md
└── images/
    ├── Capture.PNG
    ├── For Cats.PNG
    └── For Dog.PNG
```

## 🔮 Future Improvements

- Evaluate the model using a separate test set.
- Calculate accuracy, precision, recall, and a confusion matrix.
- Test more challenging images with different backgrounds and lighting.
- Export the model and build a simple web-based classifier.

## 🙏 Acknowledgments

- [Google Teachable Machine](https://teachablemachine.withgoogle.com/) for the image classification tool.
- [samuelcortinhas on Kaggle](https://www.kaggle.com/datasets/samuelcortinhas/cats-and-dogs-image-classification) for sharing the dataset.

---

**My first step into machine learning and computer vision!** 🚀
