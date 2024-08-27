# Forest Monitoring Using Hyperspectral Imagery :deciduous_tree:

## Overview :memo:

This project explores the application of hyperspectral imagery in forest monitoring, using a hybrid convolutional neural network (CNN) approach to classify various land cover types such as forests, grasslands, and agricultural fields. The project leverages the Indian Pines hyperspectral dataset to develop a model that can accurately classify and analyze different environmental features, contributing to environmental management and conservation efforts.

## Abstract :notebook_with_decorative_cover:

Forests play a crucial role in global ecosystems, making their monitoring essential for environmental sustainability. This project focuses on using hyperspectral imagery combined with a hybrid 3D-2D CNN approach to perform detailed classification of land cover types. The hyperspectral data, which contains rich spectral information, is processed to distinguish between different types of vegetation, crops, and man-made structures. The model's outputs provide valuable insights into land use, helping in environmental monitoring and land management.

## Project Goals :dart:

1. **Data Acquisition:** Obtain and preprocess hyperspectral data from the Indian Pines dataset.
2. **Model Development:** Develop a hybrid 3D-2D CNN model to classify different land cover types using spectral and spatial features.
3. **Performance Evaluation:** Assess the model's accuracy and compare it against state-of-the-art methods.
4. **Visualization:** Create classification maps and statistical reports that visually represent the distribution of various land cover types.
5. **Environmental Impact:** Use the model to support environmental management and conservation efforts by providing accurate land cover classifications.

## Technologies Used :computer:

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)](https://keras.io/)
[![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-007ACC?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)

## Methodology :gear:

1. **Data Acquisition and Preprocessing:**
   - Acquired hyperspectral data from the Indian Pines dataset.
   - Preprocessed the data to remove noise, correct for atmospheric effects, and align it with ground control points.

2. **Feature Extraction:**
   - Used a 3D CNN to extract spectral-spatial features from the hyperspectral data cube.
   - Further refined the spatial features using a 2D CNN, and concatenated the outputs to form a fused feature map.

3. **Model Training:**
   - Trained the hybrid 3D-2D CNN model on the processed data.
   - Used cross-entropy loss and the Adam optimizer for model training.

4. **Classification and Visualization:**
   - Applied the trained model to classify land cover types in the hyperspectral images.
   - Visualized the classification results using maps, graphs, and statistical reports.

5. **Performance Evaluation:**
   - Evaluated model performance using accuracy, precision, and recall metrics.
   - Compared the model’s performance with state-of-the-art methods to validate its effectiveness.

## Results :chart_with_upwards_trend:

- **Model Accuracy:** The hybrid 3D-2D CNN model achieved an overall accuracy of 99.4% on the Indian Pines dataset.
- **Key Findings:** The model was able to accurately classify various land cover types including forests, crops, and man-made structures. The classification map provided a detailed visualization of land use, aiding in environmental monitoring efforts.

## Project Folder Structure :file_folder:
```
📦 Forest_Monitoring_Using_Hyperspectral_Imagery
├── data
│ ├── Indian_Pines_Hyperspectral.csv
│ ├── Indian_Pines_Ground_Truth.csv
├── notebooks
│ └── Forest_Monitoring.ipynb
├── src
│ ├── data_preprocessing.py
│ ├── feature_extraction.py
│ ├── model_training.py
│ └── classification.py
├── results
│ └── classification_map.png
└── README.md
```

## How to Run Locally :house:

1. **Clone the repository:**
   ```bash
   git clone <repository-link>

## Key Findings :mag:
Impact of Hyperspectral Imagery: The use of hyperspectral imagery allows for detailed analysis and classification of land cover types, significantly improving the accuracy of environmental monitoring.
Hybrid CNN Model: The hybrid 3D-2D CNN model provided superior performance compared to traditional methods, demonstrating its potential for broader applications in remote sensing and environmental science.
