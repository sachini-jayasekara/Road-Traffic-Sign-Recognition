# Road Traffic Sign Recognition 

ICT3212 – Mini Project  
Implementation 1 – Image Classification using CNN

---

##  Dataset Information

- Total Classes: 10  
- Class Labels: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9  
- Total Images: 3810  
- Training Images: 3048  
- Validation Images: 762  
- Test Images: 886  
- Image Size: 64 × 64 pixels  

---

##  Model Architecture

- Conv2D (32 filters) + MaxPooling
- Conv2D (64 filters) + MaxPooling
- Conv2D (64 filters)
- Flatten
- Dense (128 neurons, ReLU)
- Output Layer (10 neurons, Softmax)

Total Parameters: 1,237,386  

Optimizer: Adam  
Loss Function: Sparse Categorical Crossentropy  

---

##  Model Performance

- Final Training Accuracy: 100%
- Final Validation Accuracy: ~99%
- Final Test Accuracy: **89.28%**
- Final Test Loss: 0.5472

---

##  Observations

- The model shows excellent performance on training and validation datasets.
- Test accuracy (89.28%) indicates good generalization.
- Slight overfitting is observed as test accuracy is lower than validation accuracy.
- Some misclassifications occur between visually similar traffic signs.

---

##  Saved Model

