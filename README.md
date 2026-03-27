# Analysing Prediction Confidence in Support Vector Machines Using Margin Distance

##  Overview
This project investigates how prediction confidence in Support Vector Machines (SVMs) can be interpreted using the distance of data points from the decision boundary, also known as margin distance.

Unlike probabilistic models, SVMs do not directly provide confidence scores. However, the decision function can be used as a proxy for confidence, where points farther from the boundary are classified with higher certainty, while points closer to the boundary are more uncertain.

---

##  Objectives
- Understand how SVM decision boundaries and margins work  
- Analyse prediction confidence using margin distance  
- Identify low-confidence and high-confidence predictions  
- Study misclassified samples and their relationship to the decision boundary  
- Evaluate the effect of the regularisation parameter (C) on model behaviour  

---

##  Experiments Conducted
The following analyses were performed:

1. Decision boundary and margin visualisation  
2. Confidence distribution analysis using decision function values  
3. Identification of low-confidence and high-confidence samples  
4. Misclassification analysis near the decision boundary  
5. Accuracy comparison across confidence levels  
6. Effect of regularisation parameter (C) on accuracy, confidence, and support vectors  

---

##  Key Findings
- Points close to the decision boundary have lower confidence  
- Misclassified samples are mostly located near the boundary  
- High-confidence regions have significantly higher accuracy  
- Margin distance provides a meaningful interpretation of prediction confidence  
- The regularisation parameter (C) affects both model complexity and confidence distribution  

---

##  Technologies Used
- Python  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

##  Project Structure
.
├── notebook.ipynb  
├── README.md  
├── requirements.txt  
└── LICENSE  

---

##  How to Run

1. Install required libraries:
   pip install -r requirements.txt  

2. Open the notebook in:
   - Jupyter Notebook  
   - Google Colab  

3. Run all cells sequentially to reproduce results  

---

##  Outputs
The project generates:
- Decision boundary visualisations with margins and support vectors  
- Confidence distribution plots  
- Visualisation of low and high confidence samples  
- Misclassification analysis plots  
- Accuracy vs confidence comparison  
- Effect of regularisation parameter (C) graphs  

---

##  References
- Cortes, C. and Vapnik, V. (1995) Support-vector networks  
- Bishop, C.M. (2006) Pattern Recognition and Machine Learning  
- James, G. et al. (2023) An Introduction to Statistical Learning  
- Scikit-learn Developers – SVM Documentation  

---

## Author
- Name: [Bala Chaithanya Borra]  
- Student ID: [24132441]  

---

