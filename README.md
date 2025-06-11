# Bioinformatics Repository 🧬🔬

Welcome to my Bioinformatics repository! This repo holds a growing collection of Jupyter notebooks focused on bioinformatics, machine learning, and deep learning—especially in the context of genomics, transcriptomics, and molecular biology (at least ones I can show). All notebooks were initially built in Google Colab, but I'm working on adding a clean Docker environment so you can run everything locally, regardless of your OS.

Why Docker? Because I roll with Mac Silicon, and I want to make sure folks using PyCharm or VS Code on Apple Silicon can spin up these projects without wrestling with package issues or compatibility headaches. The container setup will help standardize the environment across the board.

Some workflows here also used Dask for experimental reasons (on my machine out of curiosity) to scale data processing across multiple cores, even on local machines. It’s a light touch of parallelism that helps with heavy lifting in genomic datasets—so if you’re into distributed computing or planning to scale this to cloud environments later (e.g., AWS, GCP), you’re already halfway there.

Will push Docker setup soon—too many moving parts at the moment 🤯—but it’s on the roadmap. Stay tuned...


---

## 📂 Repository Contents

Below is a brief overview of the key notebooks available in this repository:

### **Graph Neural Networks (GNN) & Machine Learning**
- **`GNN_PubChem.ipynb`**: Implementation of GNN for feature engineering using PubChem datasets.
- **`Copy_of_GNN_PubChem.ipynb`**: Introduction to GNN, PCA, and feature selection.
- **`GNN_Antibiotics_expanded.ipynb`**: Application of GNN on antibiotic-related datasets.
- **`GNN_Antibiotics_with_query.ipynb`**: Query-based approach for antibiotic-related datasets.

### **Deep Learning for Bioinformatics**
- **`02_TensorFlow_Classification_TensorFlow.ipynb`**: TensorFlow-based classification model for biological sequence data.
- **`Copy_of_NB_7_GDC_API_BERT.ipynb`**: BERT model applied to genomic datasets from GDC API.
- **`PyTorch_Workflow.ipynb`**: Workflow for PyTorch-based deep learning models in bioinformatics.
- **`Positional_Encodings.ipynb`**: Exploring positional encoding in transformer architectures.

###  **Genomic & Clinical Data Analysis**
- **`Copy_of_Nat_2024_Regression_Analysis.ipynb`**: Regression analysis on biological datasets.
- **`Copy_of_Natesh__growth_maturation_tf_colab.ipynb`**: Examining transcription factor correlation with growth and maturation.
- **`Copy_of_VascuLogic_Model_2.ipynb`**: Clinical information query from fda api applications.

###  **Object-Oriented Programming (OOP) & Utilities**
- **`OOP_introduction.ipynb`**: Introductory guide to OOP concepts with Python.
- **`Bioinformatic_Tools_Hard_Coded_Python.ipynb`**: Collection of hard-coded bioinformatics utilities in Python.

---

## Technologies Used
This repository primarily utilizes:
- **Python** (NumPy, Pandas, SciPy)
- **TensorFlow / PyTorch** (for deep learning applications)
- **scikit-learn** (for classical machine learning models)
- **Graph Neural Networks (GNNs)** (via PyTorch Geometric)
- **Google Colab** (as the main computational environment)

---

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/Bioinformatics.git

