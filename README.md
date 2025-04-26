# 🔍 SMS Spam Detection - Machine Learning Project
**By [Vishwas BA]** | 

![Python](https://img.shields.io/badge/Python-3.9%2B-blue) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0-orange) ![NLP](https://img.shields.io/badge/Natural%20Language%20Processing-Applied-brightgreen)

## 🚀 Project Overview
A production-grade spam classifier achieving **98.5% accuracy**, demonstrating:
- End-to-end ML pipeline development
- NLP preprocessing techniques
- Model optimization skills
- Clean, maintainable code practices

## 🛠 Technical Implementation
### Core Stack
- **Python 3.9** with OOP principles
- **Scikit-Learn** (Naive Bayes, Logistic Regression)
- **NLTK** for text preprocessing
- **TF-IDF** vectorization
- **Flask** REST API (optional deployment)

### Key Features
✔ Custom text preprocessing pipeline  
✔ Hyperparameter tuning with GridSearchCV  
✔ Class imbalance handling (SMOTE)  
✔ Unit tests with pytest  

## 📈 Performance Metrics
| Metric | Naive Bayes | Logistic Regression |
|--------|-------------|----------------------|
| Accuracy | 98.2% | **98.5%** |
| Precision | 0.96 | 0.97 |
| Recall | 0.94 | 0.95 |
| F1-Score | 0.95 | 0.96 |

git clone https://github.com/Vishwasgowdaba/spam-detection.git

# Train Model
```
python train.py
```
# 
python predict.py "Claim your free prize now!"
# Output: "SPAM (99.2% confidence)"
## 📂 Project Structure
📦 spam-detector
├── 📂 data
│ ├── 📄 sms_spam.csv
│ └── 📂 processed
├── 📂 models
│ └── 📄 spam_model.pkl
├── 📂 notebooks
│ ├── 📄 EDA.ipynb
│ └── 📄 Modeling.ipynb
├── 📂 src
│ ├── 📄 preprocess.py
│ ├── 📄 train.py
│ └── 📄 predict.py
└── 📄 requirements.txt

## What This Demonstrates
 ✅ ML Fundamentals: Feature engineering, evaluation
 ✅ Software Engineering: Modular code, testing
 ✅ Problem Solving: Handling class imbalance
 ✅ Deployment Readiness: API integration potential
