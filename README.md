# Wine Quality Prediction

This project predicts the quality of wine based on physicochemical tests using multiple Machine Learning models.

## Table of Contents
- [Project Overview](#project-overview)
- [Models Implemented](#models-implemented)
- [How to Run](#how-to-run)
---

## Project Overview

We work with the popular **Wine Quality dataset** to predict wine ratings, link of Dataset here: https://archive.ics.uci.edu/dataset/186/wine+quality


The goal is to compare the performance of various Machine Learning models.

---

## Models Implemented

| Model | Folder | Description |
|:------|:-------|:------------|
| Multi-Layer Perceptron (MLP) | [MLP_Model/](./MLP_Model/) | Neural Network built with PyTorch |
| Classical Model | [classicalMLModels/](./classicalMLModels/) | Include many models including Logistic, Decision Tree, Random Forest, SVM |


## How to Run

Each model has its own README file and setup instructions inside its respective folder.  
Simply choose the model you want to run and follow the guide provided there.

You have two options to run the notebooks:

### Option 1: Run on Google Colab

Most notebooks are compatible with Google Colab.  
You can directly open them without any local setup.  
(Colab will automatically handle the necessary environment.)

Link Colab for Classical Model: [Link](https://colab.research.google.com/drive/19GFtHgViRoIRam-pJpCWCbjrNYIMVl2c?usp=sharing)  

Link Colab for MLP Model: [Link](https://colab.research.google.com/drive/1kxoicknnPVDTeKmb--XBSCYJLI3n3F2i#scrollTo=1nf96dCjLVL5) 

### Option 2: Run Locally with Miniconda:
If you prefer to run locally, make sure you have [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed.  
Then, follow these general steps to set up your environment:

#### 1. Install Miniconda

You can download and install Miniconda from the [official website](https://docs.conda.io/en/latest/miniconda.html).

#### 2. Clone the repository

```bash
git clone https://github.com/Bao-Trinh-Quoc/WineQualityPrediction.git
cd WineQualityPrediction
```

#### 3. Create and activate a new Conda environment

```bash
conda create -n wine_quality python=3.10
conda activate wine_quality
```

#### 4. Install the required libraries

Navigate into the specific model folder (e.g., `MLP_Model/`) and install the dependencies:

```bash
cd MLP_Model
pip install -r requirements.txt
```

#### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Then open the corresponding `.ipynb` file to start experimenting!

---
