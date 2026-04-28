## 📖 Overview
This Final Year Project (FYP) implements a hybrid machine learning approach for breast cancer prediction by combining **Support Vector Machine (SVM)** and **XGBoost** through a **soft voting ensemble classifier**. The goal is to improve predictive robustness and accuracy beyond standalone models, providing a reliable computational tool for early diagnosis support.

## ✨ Key Highlights
- **Hybrid Ensemble Architecture**: Soft voting classifier integrating SVM & XGBoost
- **High Performance**: `98.25%` test accuracy, outperforming standalone SVM (`96.49%`) and XGBoost (`97.66%`)
- **Robust Metrics**: Precision: `98.29%` | Recall: `98.25%` | F1-Score: `98.24%`
- **High Confidence**: Log Loss of `0.0665` with near-perfect classification (only 3 misclassified malignant cases)
- **End-to-End Pipeline**: Data preprocessing, model training, evaluation, and visualization

## 🛠️ Tech Stack
- **Language**: Python 3.x
- **Core Libraries**: `scikit-learn`, `xgboost`, `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`
- **Environment**: Jupyter Notebook / VS Code

**Confusion Matrix Insight**: 
- ✅ `107` Benign cases correctly classified
- ❌ Only `3` Malignant cases misclassified *(minimizing false negatives is critical in medical diagnostics)*

## 📁 Project Structure
```
├── data/                 # Raw & processed datasets
├── notebooks/            # Jupyter notebooks for EDA & experimentation
├── models/               # Saved trained models (.pkl)
├── src/                  # Modular Python scripts (preprocessing, training, evaluation)
├── app.py                # Streamlit/Gradio deployment script (optional)
├── requirements.txt      # Dependencies
└── README.md             # This file
```

## 🔮 Future Improvements
- [ ] Implement K-Fold Cross-Validation for more robust performance estimation
- [ ] Add SHAP/LIME for model interpretability & feature importance analysis
- [ ] Optimize hyperparameters using Optuna or GridSearchCV
- [ ] Deploy as a secure web app with user authentication & audit logging
- [ ] Test on external/clinical datasets for generalization

## 📜 License
This project is developed for academic & research purposes. Feel free to use, modify, and distribute.

## 👨‍💻 Author
**Muhamad Adam Irfan**  
📧 muhamadadamirfanmohdnizam@gmail.com | 🔗 [LinkedIn](https://www.linkedin.com/in/adam-irfan) | 🎓 B.Comp Science, UTP
