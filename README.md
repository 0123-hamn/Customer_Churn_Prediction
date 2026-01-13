📊 Customer Churn Prediction App

A Machine Learning web application built with Streamlit that predicts whether a customer is likely to churn based on demographic and financial information.
The model is trained using TensorFlow/Keras, with preprocessing handled via Scikit-learn.

🚀 Deployed on Streamlit Cloud

🔗 Live Demo

👉 https://customerchurnprediction-ah56raekwhjdqolhysrzro.streamlit.app/


🧠 Model Overview

Algorithm: Artificial Neural Network (ANN)

Framework: TensorFlow / Keras

Problem Type: Binary Classification (Churn / No Churn)

Output: Churn probability (0–1)

🛠️ Tech Stack

Python

Streamlit

TensorFlow

Scikit-learn

Pandas

NumPy

📂 Project Structure
├── app.py
├── model.h5
├── scaler.pkl
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl
├── requirements.txt
└── README.md

⚙️ Installation (Run Locally)
1️⃣ Clone the repository
git clone https://github.com/your-username/customer-churn-streamlit.git
cd customer-churn-streamlit

2️⃣ Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the Streamlit app
streamlit run app.py

📦 Requirements (requirements.txt)

Make sure your requirements.txt contains:

streamlit
tensorflow
scikit-learn
pandas
numpy

☁️ Deploying on Streamlit Cloud

Push your project to GitHub

Go to 👉 https://streamlit.io/cloud

Click New app

Select:

Repository

Branch (usually main)

File path: app.py

Click Deploy

✅ Your app will be live in a few seconds.

🖥️ App Features

User-friendly UI with sliders and dropdowns

Real-time churn probability prediction

Encoded categorical features (Gender, Geography)

Scaled numerical inputs for accurate predictions

📈 Output Interpretation

Churn Probability > 0.5 → Customer likely to churn

Churn Probability ≤ 0.5 → Customer not likely to churn

📸 Screenshots

<img width="1908" height="1064" alt="image" src="https://github.com/user-attachments/assets/a98c47d5-cbb6-4a49-87ce-9b10ccb2c502" />


🙋 Author

Hemanta Ghosh
📧 hemantaghosh009@gmail.com
🔗 https://www.linkedin.com/in/hemanta-ghosh-13448931b/

⭐ Acknowledgements

Streamlit
TensorFlow
Scikit-learn
