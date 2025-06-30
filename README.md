# Customer-churn-prediction


This is a Streamlit-based web application that predicts the likelihood of a customer churning (leaving) a bank based on user-input features. It uses a pre-trained TensorFlow model along with saved encoders and a scaler for accurate predictions.

---

## Features

- Predicts customer churn using a machine learning model.
- Interactive web interface to input customer details.
- Provides churn probability and a recommendation.
- Uses saved model, label encoder, one-hot encoder, and feature scaler for preprocessing.

---

## Tech Stack

- Python
- Streamlit
- TensorFlow (Keras)
- Scikit-learn
- Pandas, NumPy
- Pickle for serialized models and encoders

---

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
````

### 2. Set up a Virtual Environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Ensure the following files are in the project directory:

* `model.h5` (trained model)
* `label_encode_gender.pkl`
* `onehot_encoder_geo.pkl`
* `scaler.pkl`

### 5. Run the App

```bash
streamlit run app.py
```

---

## Input Features

* Geography
* Gender
* Age
* Balance
* Credit Score
* Estimated Salary
* Tenure
* Number of Products
* Has Credit Card (0/1)
* Is Active Member (0/1)

---

## Output

* Churn Probability (value between 0 and 1)
* A message indicating whether the customer is likely to churn

---

## Example Use Case

Useful for bank customer retention teams to quickly evaluate churn risk based on customer data and take proactive actions.

---

## License

This project is licensed under the MIT License.

```

