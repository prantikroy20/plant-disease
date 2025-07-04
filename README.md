Perfect! Since your project includes **train and test datasets**, let’s update your `README.md` to reflect that clearly — including dataset structure, loading method, and usage.

---

### 📄 Updated `README.md` (with Train/Test Data Info)

```markdown
# 🌿 Plant Disease Detection using CNN

This project uses **Convolutional Neural Networks (CNN)** to detect plant diseases from leaf images. It classifies leaves into healthy or diseased categories using a trained deep learning model.

---

## 📌 Features

- 🧠 CNN-based image classification
- 🔍 Real-time disease prediction
- 📸 Input: Leaf images
- 🧪 Uses separate **training** and **testing** datasets
- 📊 Accuracy and loss tracking via matplotlib
- 🔧 Easily deployable with Flask or Streamlit

---

## 🗂️ Dataset

The dataset is divided into two folders:

```

dataset/
├── train/
│   ├── Apple\_\_\_Black\_rot/
│   ├── Tomato\_\_\_Early\_blight/
│   └── ...
└── test/
├── Apple\_\_\_Black\_rot/
├── Tomato\_\_\_Early\_blight/
└── ...

````

- Each subfolder contains images of leaves for a specific disease.
- The dataset is sourced from the [PlantVillage dataset](https://www.kaggle.com/datasets/emmarex/plantdisease).

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/prantikroy20/plant-disease-detection.git
   cd plant-disease-detection
````

2. **Install Required Libraries**

   ```bash
   pip install -r requirements.txt
   ```

3. **Train the Model**
   Open the notebook:

   ```
   plant_disease_cnn.ipynb
   ```

   * It loads `train/` and `test/` datasets using `ImageDataGenerator`
   * Trains CNN on training data and evaluates on test data

4. **Run the Web App (optional)**

   ```bash
   streamlit run app.py
   ```

   or

   ```bash
   python app.py  # for Flask version
   ```

---

## 🧠 Model Architecture

A custom CNN with:

* Convolution layers
* MaxPooling
* Dropout
* Fully connected Dense layers
* Softmax output for multi-class classification

---

## 📈 Training Performance

Includes visualizations for:

* Training vs validation accuracy
* Training vs validation loss

---

## 📧 Contact

**Prantik Roy**
📧 [prantikr82@gmail.com](mailto:prantikr82@gmail.com)
🔗 [GitHub](https://github.com/prantikroy20) | [LinkedIn](https://linkedin.com/in/prantik-roy-300771225/)

```

---

Let me know if:
- You want help generating a `requirements.txt`
- You want this turned into a `Streamlit` app
- You’d like badges or GitHub Actions setup

Just say the word!
```
