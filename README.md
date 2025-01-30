# Breast Cancer Tumor Prediction Model

This project is a simple machine learning model that predicts whether a tumor is malignant or benign using three different classification algorithms: Naïve Bayes, Decision Tree, and K-Nearest Neighbors (KNN). The dataset used for training and testing the model is `breastcancer.csv`.

## Features
- Uses Naïve Bayes, Decision Tree, and KNN classifiers
- Trained on `breastcancer.csv` dataset
- Implements data preprocessing and model evaluation
- Easily executable in Jupyter Notebook

## Installation and Usage
### Prerequisites
Ensure you have Python installed along with the required libraries. You can install them using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Running the Project
1. Clone the repository:
   ```bash
   git clone <your-repo-link>
   cd <your-project-folder>
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `Breast_Cancer_Tumor_Prediction_Model.ipynb` and run all the cells.

## Dataset
The `breastcancer.csv` file contains features related to breast cancer tumors, which are used to train and test the model.

## Algorithms Used
1. **Naïve Bayes** - A probabilistic classifier based on Bayes' theorem.
2. **Decision Tree** - A tree-structured classifier that makes decisions based on feature conditions.
3. **K-Nearest Neighbors (KNN)** - A non-parametric method that classifies based on the majority vote of nearest neighbors.

## Results
After training, the model evaluates each algorithm's performance using accuracy, precision, recall, and confusion matrices.

## Contributing
Feel free to fork this repository and contribute improvements.

## License
This project is open-source and available under the [MIT License](LICENSE).

---
**Author:** Akriti Wagle

