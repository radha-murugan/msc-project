# Brain Tumor Survival Prediction Using Explainable AI Techniques

This repository contains the full source code for the MSc Computing Project. 
The project builds an end-to-end deep learning pipeline for automated brain tumour classification from MRI scans, using transfer learning (ResNet50) and three explainable AI techniques — Test-Time Augmentation, Grad-CAM, and Monte Carlo Dropout.

## Dataset

The dataset is **not included** in this repository due to size. Download it from Kaggle before running the notebooks:

**[Kaggle Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)**

After downloading, unzip and place the folders so your directory looks like this:


```
msc-project/
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_model_training.ipynb
│   ├── 03_regular_and_tta_evaluation.ipynb
│   ├── 04_gradcam_visualization.ipynb
│   ├── 05_gradcam.ipynb
│   └── 06_model_training_cnn.ipynb
├── data/
│   ├── Training/
│   │   ├── glioma/
│   │   ├── meningioma/
│   │   ├── notumor/
│   │   └── pituitary/
│   └── Testing/
│       ├── glioma/
│       ├── meningioma/
│       ├── notumor/
│       └── pituitary/
└── README.md
```

## Running the Notebooks

Run the notebooks **in the below order** — each one saves outputs that the next one depends on.

1. 01_data_preparation.ipynb
2. 02_model_training.ipynb and 06_model_training_cnn (can run in parllel)
3. 03_regular_and_tta_evaluation.ipynb
4. 04_gradcam_visualization.ipynb
5. 05_additional_analysis.ipynb

## Saved Models

Trained model weights are **not included** in this repository due to size

Please run the notebooks in order and it will create a folder and save the weights and training.

## License

This code is shared for academic and educational purposes.
