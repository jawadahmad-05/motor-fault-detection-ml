# Motor Fault Detection using Machine Learning

This project focuses on **predictive maintenance for induction motors** using machine learning models.  
The dataset consists of three-phase current signature data of motors under **healthy** and **faulty** conditions (bearing faults and rotor bar faults).  
The goal is to build models that can accurately classify motor health conditions for industrial applications.

---

## 📂 Project Structure
- `knn_pca.ipynb` – KNN implementation with dimensionality reduction (PCA)
- `logistic_regression.ipynb` – Logistic Regression (binary + multiclass classification)
- `naive_bayes_svm.ipynb` – Naive Bayes and Support Vector Machine
- `requirements.txt` – Python dependencies

---

## 🗂️ Dataset
The dataset used in this project includes three-phase current signals collected under:
- **Healthy motor**
- **Bearing faults** (inner-race and outer-race, with different severity levels)
- **Broken rotor bar fault**
- Various load conditions (100W, 200W, 300W)

⚠️ **Note**: The dataset is **not included in this repository** due to size and usage constraints.  
If you would like access to the dataset for research or testing purposes, please contact me via email:  
📧 **syedjawadqaisar@gmail.com**

---

## ⚙️ Models Implemented
1. **KNN with PCA**  
   - Binary classification (healthy vs unhealthy)  
   - Multiclass classification (14 classes)  

2. **Logistic Regression**  
   - Binary classification  
   - Multiclass classification  

3. **Naive Bayes & SVM**  
   - Binary classification  
   - Multiclass classification  
   - Accuracy & loss curves plotted  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/jawadahmad-05/motor-fault-detection-ml.git
   cd motor-fault-detection-ml
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open Jupyter notebooks:
   ```bash
   jupyter notebook notebooks/
   ```
---
