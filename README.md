# OHRC Crater and Boulder Detection

## Overview
This repository is dedicated to the detection of craters and boulders from the Orbiter High-Resolution Camera (OHRC) data. Our workflow involves collecting and processing lunar surface images, applying various data engineering techniques, training a machine learning model, and generating the ultimate output for accurate crater and boulder detection.

## Table of Contents
- [Overview](#overview)
- [Data Collection](#data-collection)
- [Data Engineering](#data-engineering)
  - [Augmentation](#augmentation)
  - [Preprocessing](#preprocessing)
- [Model Training](#model-training)
- [Detection and Output](#detection-and-output)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Data Collection
The dataset used in this project consists of high-resolution images captured by the OHRC, which provide detailed views of the lunar surface. The images are meticulously annotated to identify craters and boulders, forming the foundation for our detection model.

## Data Engineering
### Augmentation
Data augmentation techniques are applied to enhance the dataset's diversity and improve the model's generalization capabilities. Techniques such as rotation, scaling, flipping, and brightness adjustments are used to create a robust dataset.

### Preprocessing
Before feeding the data into the model, it undergoes several preprocessing steps, including normalization, resizing, and other transformations to ensure consistency and compatibility with the model's input requirements.

## Model Training
The core of this project is the machine learning model trained on the annotated dataset. We utilize the Roboflow platform to streamline the training process, leveraging its tools for data management, augmentation, and model training. The chosen model architecture is designed to accurately detect craters and boulders, even in challenging lunar terrains.

## Detection and Output
The trained model is deployed to perform real-time detection of craters and boulders from new OHRC images. The output includes not only the detection results but also additional metadata, such as the size, shape, and selenographic coordinates of the detected features.

## Installation
To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/OHRC_Crater_and_Boulder_Detection.git
cd OHRC_Crater_and_Boulder_Detection
pip install -r requirements.txt
```
## Results
The results section provides a summary of the model's performance, including accuracy metrics, sample detection images, and a discussion of the results.

## Contributing
We welcome contributions from the community! If you'd like to contribute, please fork the repository, make your changes, and submit a pull request. Please ensure that your code follows the project's coding standards.

## Acknowledgements
We would like to thank the organizations and individuals who provided the OHRC data and supported the development of this project.


