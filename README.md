# Feature Selection Techniques in Machine Learning

This repository provides a practical tutorial on feature selection methods in machine learning. It covers three major categories: filter methods, wrapper methods, and embedded methods. The notebook uses the Breast Cancer Wisconsin dataset and demonstrates multiple approaches with real code examples and interpretation.

## Contents

- feature_selection_methods_tutorial.ipynb : Main notebook with explanations, code, and plots
- README.md : Project overview and instructions
- requirements.txt : Python libraries needed to run the notebook
- LICENSE : Optional open-source license
- tutorial.docx / tutorial.pdf : Final formatted report (if required for submission)

## Dataset

We use the Breast Cancer Wisconsin dataset, available from scikit-learn. It contains 30 numeric features and a binary classification target (malignant or benign tumor).

## What You Will Learn

- What feature selection is and why it's important
- How to use filter methods like SelectKBest
- How to apply wrapper methods such as Recursive Feature Elimination (RFE)
- How to interpret embedded methods using Lasso and Random Forest
- How to visualize and compare selected features

## How to Run

1. Clone the repository:
```
git clone https://github.com/your-username/feature-selection-tutorial.git
cd feature-selection-tutorial
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Launch the notebook:
```
jupyter notebook feature_selection_methods_tutorial.ipynb
```

---

## Accessibility Considerations

- All code is explained using full-sentence markdown cells
- Plots are colorblind-safe and include labeled axes and titles
- Notebook is structured for screen-reader compatibility
- The layout follows a clear sequence: theory → implementation → result

---

---

## Acknowledgements

- Dataset and tools from the scikit-learn library
- Lasso and RFE models from sklearn.linear_model and sklearn.feature_selection
- Visualization libraries: matplotlib and seaborn
