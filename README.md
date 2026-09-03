# 🌸 Flower Classification using CNN

A Convolutional Neural Network (CNN) built to classify flower images into two categories: **Rose** and **Sunflower**.

## 📌 Overview

This project uses deep learning (CNN) to identify whether a given flower image is a rose or a sunflower. The model is trained on a subset of the popular Kaggle Flowers Recognition dataset.

## 📂 Dataset

- **Source:** [Flowers Recognition Dataset – Kaggle](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition)
- The original dataset contains 5 classes: daisy, dandelion, rose, sunflower, and tulip.
- **This project uses only 2 classes: Rose and Sunflower.**
- Due to size constraints, the full dataset is **not included** in this repository. To use it yourself:
  1. Download the dataset from the Kaggle link above (or use the Kaggle API: `kaggle datasets download -d alxmamaev/flowers-recognition`)
  2. Extract it, and keep only the `rose/` and `sunflower/` folders
  3. Place them in a `data/` folder in the project root before running the notebook

## 🧠 Model

- Built using a Convolutional Neural Network (CNN)
- Trained to classify images into 2 classes: Rose, Sunflower
- Framework: TensorFlow / Keras

## 📁 Repository Structure

```
flower-classification-cnn/
│
├── flower.ipynb        # Main notebook with data preprocessing, model building, training & evaluation
├── test.jpg            # Sample test image (rose)
├── test1.jpg           # Sample test image (sunflower)
└── README.md            # Project documentation
```

## 🚀 How to Run

1. Clone this repository:
   ```
   git clone https://github.com/<your-username>/flower-classification-cnn.git
   ```
2. Download the dataset as described above and place `rose/` and `sunflower/` folders inside a `data/` directory.
3. Open `flower.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells to preprocess the data, train the CNN, and evaluate results.
5. Use the provided `test.jpg` / `test1.jpg` images (or your own) to test predictions.

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy, Matplotlib
- Jupyter Notebook

## 📊 Results

*(Add your model's accuracy, sample predictions, or a confusion matrix here once available.)*

## 📌 Notes

- This is a subset project focusing only on 2 out of the 5 available flower classes for simplicity and faster experimentation.
- Feel free to extend the model to all 5 classes using the same approach.

## 🙌 Acknowledgements

- Dataset: [Flowers Recognition on Kaggle](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition)
