## OverView
This project uses a Convolutional Neural Network (CNN) to classify images into four weather categories: **cloudy**, **rain**, **shine**, and **sunrise**. It involves image preprocessing, model training and validation, prediction, and data augmentation using TensorFlow and Keras in Google Colab.




## ⚙️ Technical Details

### 🔹 CNN Model Architecture
- 3 convolutional + max pooling layers  
- Flatten layer  
- 2 dense (fully connected) layers  
- Softmax output for 4-class classification


## 🧪 Data Preprocessing
- All images resized to **300x300** with RGB channels  
- Labels encoded with One-Hot Encoding  
- Dataset shuffled and split into training and validation sets (approximately 75% train, 25% validation)  
- Test dataset contains 75 images  



## 📊 Model Training
- **Epochs**: 30  
- **Batch Size**: 32  
- **Optimizer**: Adam (`learning_rate = 0.0001`)  
- **Loss Function**: Categorical Crossentropy  
- Final training accuracy: **100%**  
- Validation accuracy: around **87%–89%**  
- Training process visualized with loss and accuracy plots  

---

## ✅ Prediction Output
- Model makes predictions on 75 test images  
- Predictions saved to `predict_label.csv` in the following format:


