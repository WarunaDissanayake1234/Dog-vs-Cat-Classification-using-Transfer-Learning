
# Dog vs Cat Classification using Transfer Learning

This repository contains code for a Convolutional Neural Network (CNN) model that classifies images into either dog or cat categories using transfer learning with a pre-trained MobileNetV2 model.

## Overview

This project utilizes transfer learning with a pre-trained MobileNetV2 model to implement a classification model for distinguishing between dogs and cats in images. Python programming language is used for implementation, and TensorFlow and TensorFlow Hub are employed for building and training the model. The architecture of the model includes Convolutional Neural Network layers.

## Requirements

- Python
- Jupyter Notebook or Python IDE (for running the code)
- Libraries: kaggle, opencv-python, tensorflow, tensorflow-hub

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/WarunaDissanayake1234/Dog-vs-Cat-Classification.git
   ```

2. **Install Dependencies:**
   - Install the required libraries:
   ```bash
   pip install kaggle opencv-python tensorflow tensorflow-hub
   ```

3. **Download the Pre-trained Model:**
   - Download the MobileNetV2 pre-trained model from [TensorFlow Hub](https://tfhub.dev/google/tf2-preview/mobilenet_v2/feature_vector/4).

4. **Run the Code:**
   - Open the Jupyter Notebook or Python script.
   - Follow the instructions within the notebook/script to import dependencies, load the pre-trained MobileNetV2 model, build the CNN architecture, and train the model for dog vs cat classification.

## Files

- `dog_vs_cat_classification.ipynb`: Jupyter Notebook containing the code for dog vs cat classification using transfer learning and CNN architecture.

## Acknowledgments

The pre-trained MobileNetV2 model used for this project is sourced from [TensorFlow Hub](https://tfhub.dev/google/tf2-preview/mobilenet_v2/feature_vector/4).

