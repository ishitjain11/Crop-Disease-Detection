# Crop Disease Detection Using Deep Learning

This project focuses on detecting plant diseases from leaf images using deep learning models.

We used the PlantVillage dataset and trained different deep learning models for classification of healthy and diseased plant leaves.

## Dataset

We used the PlantVillage dataset, which contains:

- 54,305 images
- 38 classes
- Images of healthy and diseased plant leaves

The dataset was divided into:

- 60% Training
- 20% Validation
- 20% Testing

## Methodology

The images were first resized to `299 x 299` and normalized.

The main steps followed were:

1. Dataset collection
2. Image preprocessing
3. Dataset splitting
4. Model training
5. Model testing
6. Performance comparison

We trained deep learning models including:

- AlexNet
- VGG

Adam optimizer was used for training with a learning rate of `0.001`. StepLR was used for learning rate scheduling.

## Technologies Used

- Python
- PyTorch
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Results

The models were evaluated using the test dataset.

We compared the models based on their classification performance and used accuracy and Precision-Recall curves for evaluation.

## Project Structure

```text
Crop-Disease-Detection/
│
├── notebooks/
├── models/
├── dataset/
├── results/
├── requirements.txt
└── README.md


How to Run

Clone the repository:
git clone https://github.com/ishitjain11/Crop-Disease-Detection.git
cd Crop-Disease-Detection

Install the required libraries:
pip install -r requirements.txt

Download the PlantVillage dataset and place it in the required dataset folder.
Open the Jupyter Notebook and run the cells to train and test the model.
