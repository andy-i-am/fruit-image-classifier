# 🍎🍅 Fruit Image Classifier

UiA IKT902 course project — image recognition model using Teachable Machine (apples vs. tomatoes).

---

### 📖 About the project
This project was created as part of the **IKT902 – Introduksjon til kunstig intelligens-teknologi** course at the **University of Agder (UiA)**.  
The goal was to train a simple image recognition model using **Google Teachable Machine** to distinguish between **apples** and **tomatoes**.

---

### 🧠 Model details
- **Platform:** Teachable Machine (Image Project)  
- **Classes:** Apple, Tomato  
- **Training images:** Custom dataset (train/test split)  
- **Parameters:** Epochs = 50, Batch size = 16, Learning rate = 0.001  
- **Accuracy:** 100 % on the test set  
- **Export format:** TensorFlow.js

---

### 📂 File overview
- `model.json` — model architecture and configuration  
- `metadata.json` — class information (apple, tomato)  
- `weights.bin` — trained neural network weights 

These files were exported from Teachable Machine in **TensorFlow.js** format and can be loaded directly in a web project.

---

### 🧪 Testing
The model was tested with images not seen during training (test set).  
All images were correctly classified, showing clear visual separation between the two fruit types.  
However, further tests with more varied data are recommended to check real-world robustness.

---

### ✍️ Author
**Andy-I-Am**
*UiA IKT902 – Autumn 2025*
⸻
