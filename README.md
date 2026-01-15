# HAND-AID: Detection of AI-Generated answers from Handwritten answer scripts using Image Processing

This repository contains the source code and datasets for a project focused on processing and analyzing handwritten documents.

## Project Structure

* **Handwritten PDF SS**: Contains scanned images of the handwritten answer scripts.
* **Original.zip**: The original answers dataset of handwritten scripts used for training and testing the model.
* **AI Generated.zip**: AI-generated answers of the same questions to train and test the model.
* **Dataset Img Processing-5-Fold CV.ipynb**: Code file in which 5-fold cross-validation and image preprocessing techniques are applied to the dataset.

## 🚀 Getting Started

### Prerequisites
* Python 3.x
* Required libraries: `opencv-python`, `numpy`, `pandas`, `PIL` (Pillow)

### Installation
1. Clone the repository   
2. Unzip the datasets:
   
   a. unzip Original.zip -d data/raw
   
   b. unzip AI\ Generated.zip -d data/augmented

### Features
1. **Image Preprocessing**: Handles noise reduction and normalization for handwritten text.
2. **5-Fold Cross-Validation**: Ensures robust model evaluation by splitting the dataset into five distinct folds.
3. **Data Augmentation**: Includes altered or modified data to improve model accuracy on rare handwriting styles.
