Explainable AI: Income Prediction and Bias Analysis

This project uses the UCI Adult Census Income dataset to predict whether an individual earns more than $50K per year.

The first option is to run it in Google Colab:
1. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MaritRokx/Explainable-AI/blob/main/ExplainableAIFinal.ipynb)  
2. you must download the `adult.data` and `adult.test` files from this repository and manually upload them into your Colab session's file explorer before running the code.

You could also do it locally: 
1. Clone this repository to your computer
2. Ensure the `adult.data` and `adult.test` files are located in the exact same directory as the Jupyter Notebook.
3.  Install the required dependencies:
   ```bash
   pip install shap dice-ml scikit-learn pandas numpy matplotlib
