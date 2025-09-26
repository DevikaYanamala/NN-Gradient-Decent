# NN-Gradient-Decent

# 🧠 Neural Network & Gradient Descent (Insurance Dataset)

This project builds a simple **Neural Network (NN)** from scratch using **NumPy** and trains it with **Gradient Descent** on the **Insurance dataset**.  
The aim is to predict **medical insurance charges** based on demographic and lifestyle features.

---

## 📊 Dataset Overview
The dataset (`insurance.csv`) contains information about insurance customers with the following columns:
- **age** → Age of the individual  
- **sex** → Gender (`male`, `female`)  
- **bmi** → Body mass index  
- **children** → Number of children/dependents  
- **smoker** → Smoking status (`yes`, `no`)  
- **region** → Residential region  
- **charges** → Medical insurance cost (target variable)  

---

## 📊 Project Workflow
1. Load the dataset with **pandas**  
2. Preprocess categorical variables (encode `sex`, `smoker`, `region`)  
3. Normalize numerical features  
4. Initialize a simple **Neural Network** architecture using NumPy  
   - Input layer → Hidden layer(s) → Output layer  
5. Implement **forward propagation**  
6. Define **loss function** (Mean Squared Error)  
7. Implement **backpropagation** with Gradient Descent  
8. Train the model and evaluate predictions against actual charges  

---

## ⚙️ Features
- Fully implemented **forward and backward propagation** from scratch  
- Gradient Descent optimization without high-level frameworks  
- Predicts **insurance charges** (regression problem)  
- Demonstrates the mechanics of neural networks at a low level  

---

## 🚀 Tech Stack
- **Python 3**  
- **NumPy** → matrix operations & math  
- **pandas** → dataset handling  
- **scikit-learn** → preprocessing, train/test split  


---

## 🔧 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/DevikaYanamala/nn-gradient-descent-insurance.git
   cd nn-gradient-descent-insurance
   pip install -r requirements.txt
   jupyter notebook NN_gradient_descent.ipynb



