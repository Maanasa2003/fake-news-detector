## Fake News Detector

### Research Question
"Can machine learning and transformer-based deep learning models effectively detect misinformation in short political statements, and how do they compare in performance?"

### Dataset
LIAR dataset — 10,240 labelled political statements

### Approach
1. EDA and text preprocessing
2. TF-IDF feature engineering
3. ML baseline models (Logistic Regression, Random Forest, XGBoost)
4. DistilBERT transformer model
5. Comparison and deployment

### Results So Far
| Model | Accuracy | F1 Score |
|-------|----------|----------|
| Logistic Regression | 0.61 | 0.659 |

### Key EDA Findings
- Real statements use quantifiable language
- Fake statements are more person focused
- Context matters more than word presence alone

### Tech Stack
Python, scikit-learn, HuggingFace, Streamlit

#### Live Demo
Coming soon
