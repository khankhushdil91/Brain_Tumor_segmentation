# Multimodality Brain Tumor Segmentation using AI

This repository contains the code for the project "Multimodality Brain Tumor Segmentation using AI." The project leverages deep learning techniques to segment brain tumors from multimodal medical images.

## Table of Contents
- [Introduction]
- [Project Structure]
- [Installation]
- [Usage]
- [Results]
- [Contributing]
- [Acknowledgements]

## Introduction

Brain tumor segmentation is a critical task in medical image analysis, aiding in the diagnosis, treatment planning, and monitoring of brain tumors. This project implements a deep learning model to segment brain tumors from multimodal MRI images using a 3D U-Net architecture.

## Project Structure

- Script to preprocess and prepare the BraTS 2020 dataset for training.
-  Custom data generator for loading and augmenting MRI images during training.
-  Main training script for the 3D U-Net model.
- Implementation of the 3D U-Net model architecture.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/multimodality-brain-tumor-segmentation.git
    cd multimodality-brain-tumor-segmentation
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Prepare the data:
    ```bash
    python 232_brats2020_get_data_ready.py
    ```

2. Train the model:
    ```bash
    python 234_train_brats2020_V5.0.py
    ```

3. Evaluate the model (example script needed):
    ```bash
    python evaluate_model.py
    ```

## Results

Include any visual results, metrics, or example outputs here. For example:
- Dice coefficient: X.XX
- Example segmentation results:

![Sample image 2](https://github.com/user-attachments/assets/f455ebf1-d090-4ec3-8555-2b3d0468c658)


## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.



## Acknowledgements

- BraTS 2020 organizers for providing the dataset.
- TensorFlow/Keras for the deep learning framework.
- Any other libraries or tools used in this project.

