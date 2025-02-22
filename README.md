# AI-Powered Image Analysis for Environmental Monitoring

This project uses the EuroSAT dataset to train a Convolutional Neural Network (CNN) for land cover classification. The goal is to analyze satellite images and classify them into 10 different land use and land cover (LULC) categories, such as forests, agricultural land, and urban areas.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Technologies Used](#technologies-used)

---

## Project Overview

The EuroSAT dataset contains 27,000 labeled satellite images divided into 10 classes. This project trains a CNN model to classify these images, demonstrating the application of AI in environmental monitoring and land cover analysis.

---

## Features

- **CNN Model**: A deep learning model for land cover classification.
- **Data Augmentation**: Uses `ImageDataGenerator` for preprocessing and augmentation.
- **Visualization**: Includes visualizations of training accuracy and sample predictions.
- **Model Saving**: The trained model is saved for future use.

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Suliman623/ai-environmental-monitoring.git
   cd ai-environmental-monitoring
   ```
---

## Usage

1. Open the Jupyter Notebook (`AI_Environmental_Monitoring.ipynb`).
2. Run the cells to preprocess the data, train the model, and visualize the results.
3. Use the saved model (`eurosat_cnn_model.h5`) for inference on new satellite images.

---

## Technologies Used

- **Python**: Core programming language.
- **TensorFlow/Keras**: For building and training the CNN model.
- **Matplotlib**: For visualizations.
- **NumPy**: For numerical computations.

---


## Acknowledgments

- Thanks to [EuroSAT](https://github.com/phelber/EuroSAT) for providing the dataset.
- Special thanks to the TensorFlow and Keras communities for their excellent documentation and support.

---

## Contact

For questions or feedback, feel free to reach out:

- **Muhammad Suliman**: (Sulimangorsi623@gmail.com)
