# 🫁 Pneumonia Classification Notebook  

Created by **Mohamed Islam Hadjaz** and **Adel Derradj**  

A deep learning project focused on the **detection and classification of respiratory illnesses** (pneumonia and related conditions) using chest X-ray images.  
The model was trained to classify X-ray images into **three classes**.  

---

## 📌 Project Overview
Pneumonia remains one of the most common respiratory diseases, and early detection through medical imaging can greatly improve treatment outcomes.  
This project demonstrates how deep learning can be applied in **medical image analysis** for classification tasks.  

---

## ⚙️ Workflow
1. **Dataset Preparation**  
   -  handled dataset samples (over 22000 x-ray images from a kaggle dataset)
   - Balanced classes where possible  
2. **Data Preprocessing & Augmentation**  
   - Image resizing, normalization  
   - Augmentation techniques (rotation, flipping, zoom) 
3. **Data Visualization**  
   - Plotted class distribution and sample X-rays  
4. **Data Splitting**  
   - [Training 70% / Validation 20% / Test 10%] sets created for fair evaluation  
5. **Model Development**  
   - Deep learning CNN with ~100 MB parameters  
   - Trained on Kaggle cloud services for faster results  
6. **Evaluation & Validation**  
   - Accuracy, loss curves, and confusion matrix analysis  

---

## 📊 Results
- **Test Accuracy**: **94.85%**  
- **Loss & Accuracy Curves**: Indicated strong learning with slight overfitting due to dataset quality issues  
- **Confusion Matrix**: Showed reliable classification performance across all three categories  
- **Model Size**: ~100 MB  

---

## 🛠️ Tools & Technologies
- **Languages**: Python  
- **Frameworks**: TensorFlow / Keras / PyTorch / Kaggle / jupternotebook / Googlecollab
- **Visualization**: Matplotlib, Seaborn  
- **Other**: libraries NumPy, Pandas ...ect for preprocessing
  
---
## 🚀 Key Learnings
- Handling **medical imaging datasets** with noise and corruption  
- Designing and training a **deep learning model** for real-world classification  
- Using **data augmentation** to increase performance and improve generalization  
- Evaluating models with **confusion matrices** and accuracy metrics  

---

## 📂 Future Improvements
- Expand dataset with more diverse X-rays to reduce bias  
- Experiment with transfer learning (e.g., ResNet, EfficientNet) for higher accuracy

---

## NOTE 
This model was deployed in a **web application** for clinical testing 
Hosting the model by Hugging face
  
  
