# 🎶 Songs-Genre-Classifier

Project developed for the **Data Mining and Machine Learning** course  
*MSc in Artificial Intelligence and Data Engineering – University of Pisa*  

---

## 📂 Repository Structure

| Folder / File | Description |
|---------------|-------------|
| `data/` | Dataset used for training and testing the classifier. |
| `notebooks/` | Jupyter notebooks with exploratory analysis, preprocessing, model training, and evaluation. |
| `.gitignore` | Configuration file to exclude data/artifacts from version control. |
| `Musical_Genre_Classifier_Doc.pdf` | Technical report describing the project in detail. |
| `Musical_Genre_Classifier_Slides.pdf` | Presentation slides summarizing the main results. |

---

## 🔑 Main Components

1. **Data Collection**  
   - Importing the dataset of songs with audio features.  
   - Data quality check (missing values, class distribution, redundancies).  

2. **Preprocessing & Feature Engineering**  
   - Data cleaning and feature normalization.  
   - Extraction of relevant audio features (e.g., spectral features, energy, MFCC, etc.).  
   - Dimensionality reduction when needed (PCA / feature selection).  

3. **Classification Models**  
   - Tested algorithms: *k-NN, Decision Tree, Random Forest, SVM, Neural Networks*.  
   - Training with cross-validation.  

4. **Evaluation**  
   - Metrics: *accuracy, precision, recall, F1-score, confusion matrix*.  
   - Error analysis and model comparison.  

5. **Results & Conclusions**  
   - Performance comparison across models.  
   - Identified limitations and suggestions for future improvements.  

---

## 👤 Author
Michele Meazzini
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn jupyter
