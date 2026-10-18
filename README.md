## Machine Learning Algorithm Projects

A collection of hands-on projects where I practice machine learning algorithms by applying each one to a real dataset. I'm learning consistently and adding new projects as I go.

### About this repository
I believe the best way to learn an algorithm is to **use it on real data, break it, and fix it**. For every algorithm I build a project in Google Colab that goes from raw data to a trained, evaluated and explained model. The goal is not only to get a good score, but to understand **how the algorithm works, when it fails, and how to judge it honestly**.

### What this practice improves in my skills
- **Core ML concepts:** supervised learning, regression vs classification, the bias-variance trade-off, overfitting and underfitting
- **Data preparation:** exploring data, handling missing values, encoding categorical features, scaling and train/test splitting
- **Model training:** fitting algorithms with scikit-learn and understanding what happens inside them
- **Model evaluation:** MAE, RMSE, R², accuracy, precision, recall, F1, ROC-AUC, confusion matrices and cross-validation
- **Model improvement:** hyperparameter tuning, feature engineering and handling imbalanced data
- **Interpretation:** reading coefficients, feature importance and decision rules
- **Good habits:** always comparing with a baseline, avoiding data leakage and not trusting a single score
- **Communication:** visualizing results and documenting my work clearly

### Algorithm roadmap
Tick each box as I complete a project.

- [ ] Linear Regression
- [ ] Logistic Regression
- [ ] k-Nearest Neighbors
- [ ] Decision Tree
- [ ] Random Forest
- [ ] Gradient Boosting (XGBoost / LightGBM)
- [ ] Support Vector Machine
- [ ] Naive Bayes
- [ ] k-Means Clustering
- [ ] Principal Component Analysis (PCA)
- [ ] Neural Networks

### How every project is structured
1. **Problem:** what I'm trying to predict and why it matters
2. **Data:** loading, exploring and visualizing the dataset
3. **Preparation:** cleaning, encoding and splitting the data
4. **Baseline:** a simple reference model to beat
5. **Model:** training the algorithm and learning how it works
6. **Evaluation:** metrics on unseen test data
7. **Improvement:** tuning and feature engineering
8. **Interpretation:** what the model learned
9. **Prediction:** using the model on new examples

### Tech stack
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Google Colab

### How to run
**In Google Colab:** open a notebook from the table above and run all cells. Each notebook loads its dataset by itself.

**Locally:**
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

### Repository structure
```
.
├── README.md
├── <algorithm-project-1>.ipynb
├── <algorithm-project-2>.ipynb
└── ...
```

### Notes
- These are learning projects on public sample datasets, not production systems.
- Scores can vary slightly with library versions and random seeds.
- More algorithms and projects will be added as I keep practicing.
