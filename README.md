Project: CNN-Based Brain Tumor Classification

## Dataset

This project uses the MRI dataset from Kaggle:

https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset?resource=download

### How to Download
1. Create a Kaggle account if you don’t have one
2. Go to the dataset link above
3. Click "Download"
4. Extract the files into the project directory:

The dataset consists of MRI brain scans categorized into different classes (e.g., tumor vs non-tumor), used to train a CNN for classification.

Instructions:
1. Open the .ipynb file in Google Colab
2. Mount Google Drive if dataset is stored there
3. Ensure dataset folders are structured as:
   /Training
   /Testing
4. Run all cells in order
5. Outputs will include accuracy, loss graphs, and confusion matrix

Dependencies:
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
