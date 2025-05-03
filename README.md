# Alzheimers-disease-classification


This project focuses on classifying Alzheimer's disease stages using image data through both **traditional machine learning** and **deep learning** approaches. The dataset is initially imbalanced, and later balanced using **data augmentation** techniques to improve performance.

---


---

##  Dataset

The dataset contains MRI brain scan images categorized into four classes:
-  `NonDemented`
-  `VeryMildDemented`
-  `MildDemented`
-  `ModerateDemented`

Initially, the dataset is **imbalanced**, which can bias model performance. To mitigate this, we applied **data augmentation** to artificially increase the size of minority classes.

---

##  Workflow Summary

###  1. Imbalanced Data
- Implemented traditional **machine learning algorithms** and balanced data using different
  techniques like undersampling, oversampling and SMOTE
- Found in `machinelearning.ipynb`

- Applied **deep learning and transfer learning** techniques:
  - CNN from scratch
  - Pretrained models like VGG16, ResNet50, InceptionV3
- Found in `deeplearning.ipynb`

###  2. Data Augmentation
- Used `ImageDataGenerator` to:
  - Flip
  - Rotate
  - Zoom
  - Shift images
- Found in `data_augmentation.ipynb`

###  3. Balanced Data

- Re-trained CNN and transfer learning models:
  - Found in `balanceddeeplearning.ipynb`

---

## 🛠️ Technologies & Libraries

- Python
- Jupyter Notebook
- NumPy, Pandas
- OpenCV (`cv2`)
- Matplotlib, Seaborn
- scikit-learn
- TensorFlow, Keras

---

## How to Run

 -> Clone the repo and install dependencies:

 -> pip install -r requirements.txt

  -> run the notebooks in the order:
   1.machinelearning.ipynb
   2.deeplearning.ipynb
   3.data_augmentation.ipynb
   5.balanceddeeplearning.ipynb

