# 🧠 Waste Classification Web App

Welcome to the **Waste Classification Web App** – a deep learning-powered application that classifies images of waste into predefined categories using a trained Convolutional Neural Network (CNN). Designed with sustainability in mind, this project helps automate waste sorting for better recycling and waste management.

---

## 🌍 Why Waste Classification?

Accurate and efficient waste classification is a key component of sustainable waste management. Manually sorting waste is not only time-consuming but also prone to human error. With deep learning, we can automate this process, making it faster, more reliable, and scalable.

This project helps in:
- Enhancing waste segregation at source
- Automating classification at recycling plants
- Supporting educational awareness around waste types

---

## 🚀 Project Demo

> 💡 A live demo link can be added here if deployed on Streamlit Cloud or Hugging Face Spaces.

---

## 🧾 Supported Waste Categories

The system currently classifies images into the following four classes:

| Label     | Description                                |
|-----------|--------------------------------------------|
| 📱 E-waste  | Electronic items like phones, chips, etc. |
| 🌿 Organic  | Food waste, plant material, etc.          |
| 🧴 Plastic  | Bottles, containers, wrappers             |
| 👕 Textile  | Clothes, fabric scraps, textile fibers    |

---

## 📁 File Structure

```text
waste-classification-app/
├── app.py                 # Streamlit UI for live classification
├── train_model.ipynb      # Jupyter Notebook to train the CNN model
├── test_model.ipynb       # Notebook for evaluating the model
├── Untitled1.ipynb        # Miscellaneous experimentation or scratch code
├── model/
│   └── waste_model.h5     # Trained Keras model file (user adds manually)
├── requirements.txt       # Required Python packages
└── README.md              # Project documentation (this file)
