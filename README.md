# IWP-Project

Drug Target Classification Using Machine Learning, Deep Learning, and Transformers
This project implements a complete end-to-end pipeline for drug-target prediction / text-based biological classification using multiple families of models:
- Classical Machine Learning (Logistic Regression, SVM, Random Forest)  
- Deep Learning (CNN, LSTM, CNN-LSTM hybrid)  
- Transformer-based Model (BERT fine-tuning)
The project is modular, clean, and production-ready. It is designed for research submissions, reproducibility, and easy deployment.

## 🚀 Key Features

- **Dataset Handling**
  - Loading, cleaning, splitting (train/val/test)
  - Text normalization and preprocessing
  - TF–IDF vectorization for classical ML  
  - Tokenization for deep models using BERT tokenizer  

- **Models Included**
  - Logistic Regression  
  - SVM (linear kernel)  
  - Random Forest  
  - CNN  
  - LSTM  
  - CNN-LSTM Hybrid  
  - Fine-tuned BERT classifier  

- **Training Utilities**
  - Unified training pipeline  
  - Evaluation: Accuracy, Precision, Recall, F1  
  - Reproducible splits with random seeds  

- **Clean Modular Code**
  - `src/` folder with isolated modules  
  - Easy to extend with your own model architectures  

## 📊 Dataset Format

```csv
text,target
"protein x interacts with y",1
"sequence does not form binding",0
```

## 🌐 Dataset Sources (Drug-Target / Bio)
If you need publicly available datasets, here are good options:
| Dataset | Link | Type |
|--------|------|------|
| **STRING PPI dataset** | https://string-db.org | Protein–Protein interactions |
| **BioGRID** | https://thebiogrid.org | Genetic & chemical interactions |
| **BindingDB** | https://www.bindingdb.org | Drug–target binding |
| **DrugBank** | https://go.drugbank.com | Drug target metadata |
| **ChEMBL** | https://www.ebi.ac.uk/chembl | Bioactivity datasets |
| **TDC (Therapeutics Data Commons)** | https://tdcommons.ai | ML-ready drug datasets |


