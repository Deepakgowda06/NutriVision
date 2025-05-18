# 🍽️ NutriVision

**NutriVision** is a smart food recognition system that identifies food items from images, calculates their calorie content per 100g, and provides personalized dietary plans based on nutritional data.

---

## 🔍 Features

- 📷 **Food Recognition** using a deep learning model (ResNet50)  
- 🔢 **Calorie Estimation** per 100 grams  
- 🥗 **Dietary Recommendations** based on food type and health goals  
- 🌐 Web-based interface for user-friendly access  

---


## 🧠 How It Works

1. **Upload a food image**  
2. **Model predicts the food item** (fine-tuned ResNet50)  
3. **Calories per 100g** are shown  
4. **Dietary plan** is generated based on the food and user goals  

---

## 🗂️ Project Structure

```
NutriVision/
├── app.py                  # Main Flask/Streamlit app
├── food_data.py           # Calorie and nutritional information
├── helpers.py             # Utility functions
├── resnet50_model.pth     # Trained PyTorch model
├── static/                # Images, CSS, JS (if any)
├── templates/             # HTML templates (if Flask)
└── README.md
```

---

## 📦 Installation

```bash
git clone https://github.com/Deepakgowda06/NutriVision.git
cd NutriVision
install requirements
python app.py
```

> **Note:** Large model files (.pth) may need to be downloaded separately if not included. Git LFS is recommended.

---

## 📊 Model Info

- **Base model:** ResNet50  
- **Framework:** PyTorch  
- **Dataset:** Food-80 *(or custom, if applicable)*  

---

## 🧑‍💻 Author

**Deepak Gowda**  
Final Year CSE Student, Maharaja Institute of Technology  
📍 Mandya, India  
[GitHub](https://github.com/Deepakgowda06)

---

## 📃 License

This project is licensed under the [MIT License](LICENSE).

---
