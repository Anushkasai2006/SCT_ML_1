# SCT_ML_1
House Price Prediction based on square footage
# 🏠 Task 1: House Price Prediction (India-Based)

As part of my internship on AI Agent Development, I created a deep learning model to predict house prices in Indian Rupees (₹) based on a home's physical features.

## 📌 Problem Statement
Build a machine learning regression model that can predict the price of a house in India using inputs such as:
- Square Feet
- Number of Bedrooms
- Number of Bathrooms
- Number of Halls
- Number of Kitchens

## 🧠 Technologies Used
- Python
- Pandas and NumPy
- TensorFlow / Keras
- Scikit-learn (StandardScaler)
- Gradio for interactive deployment
- Babel (for INR currency formatting)

## ⚙️ Approach
- The dataset was created manually to simulate real-world Indian housing data.
- Features were normalized using StandardScaler.
- A neural network model was built using Keras with two hidden layers (ReLU activation).
- The model was trained for 200 epochs using Mean Squared Error loss and Adam optimizer.
- Predictions were formatted in ₹ using `babel.numbers.format_currency`.

## 🖥️ Deployment
- The model is deployed via Gradio.
- Users can input square feet, number of rooms, and see the predicted house price instantly in INR.

## ✅ Sample Inputs
| Square Feet | Bedrooms | Bathrooms | Hall | Kitchen | Output (₹)        |
|-------------|----------|-----------|------|---------|-------------------|
| 1200        | 2        | 1         | 1    | 1       | ₹21,00,000         |
| 2400        | 4        | 3         | 2    | 1       | ₹52,00,000         |

## 📦 Output
The model returns the price in formatted INR currency, e.g., `₹36,00,000`.

---

📂 This task was completed as part of my AI Agent Development internship program.
