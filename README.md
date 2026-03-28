# Detecting Tuberculosis in X-Rays
This project uses a Convolutional Neural Network (CNN) to classify chest X-ray images as Tuberculosis (TB) positive or healthy. The model achieves high specificity and precision, making it effective at minimizing false positives for healthy patients.

Project Structure
.
├── data/                # X-ray images (train/test)
├── notebook.ipynb       # Jupyter notebook with code and analysis
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation

Installation
Install dependencies:

pip install -r requirements.txt

Usage
Place your X-ray images in the data/ directory, organized in subfolders for each class (e.g., TB/, Healthy/).
Open notebook.ipynb in Jupyter Notebook or JupyterLab.
Run the notebook cells to train the model, evaluate performance, and visualize results.
Results
Training accuracy: ~74%
Validation accuracy: ~86%
Sensitivity (Recall for TB): High
Specificity (True Healthy): High
Precision for TB: High
The model demonstrates strong performance, especially in correctly identifying healthy patients.

Example Plots
Confusion Matrix Metrics
Sensitivity (Recall for TB): value
Specificity (True Healthy): value
PPV (Precision for TB): value
NPV (Precision for Healthy): value

