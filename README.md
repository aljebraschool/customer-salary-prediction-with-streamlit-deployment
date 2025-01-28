# customer-salary-prediction-with-streamlit-deployment

📌 Overview

This project is a Customer Salary Prediction model deployed using Streamlit. The application allows users to input relevant customer data and receive a salary prediction based on a trained regression model.

🚀 Features

- User-friendly Streamlit web interface
- Pretrained regression model for salary prediction
- Encoders for categorical feature transformation
- Scaler for numerical feature normalization
- Easy deployment and execution

## Demo
Access the deployed app here: [Customer Churn Prediction](https://customer-churn-classifier-with-app-deployment-9etrrrg4ch7rvfz9.streamlit.app/).

## **Below is a demonstration of the app's interface:**
![image](https://github.com/user-attachments/assets/17484219-f311-4e04-95e4-cfbe8e92ef4a)

📂 Repository Structure

``` bash
📦 customer-salary-prediction-with-streamlit-deployment
├── README.md                  # Project documentation
├── regression.ipynb           # Jupyter Notebook for model training & evaluation
├── regression_model.h5        # Trained regression model (Keras/TensorFlow)
├── label_encoder_regression_gender.pkl    # Label encoder for gender feature
├── one_hot_encoder_regression_geography.pkl # One-hot encoder for geography feature
├── scaler_regression.pkl      # Scaler for feature normalization
├── streamlit_regression.py    # Streamlit app script
├── requirements.txt           # Dependencies required for running the project

```

📥 Installation & Setup
1. Clone the repository
   ``` bash
    git clone https://github.com/your-username/customer-salary-prediction-with-streamlit-deployment.git
    cd customer-salary-prediction-with-streamlit-deployment
   ```
2. Create a virtual environment (optional but recommended)
``` bash
  python -m venv venv
  source venv/bin/activate  # On macOS/Linux
  venv\Scripts\activate     # On Windows
```
3. Install dependencies
   ``` bash
    pip install -r requirements.txt  
   ```
▶️ Running the Streamlit App

Run the following command to start the Streamlit application:

``` bash
streamlit run streamlit_regression.py
```
This will launch a local web application in your browser.

📊 How It Works

- Open the Streamlit app.
- Enter the required customer details such as gender, geography, age, and other relevant features.
- Click the Predict button to get the salary prediction.

🛠 Model & Technologies Used

- Machine Learning Model: Regression (Trained using TensorFlow/Keras)

- Libraries:

  - Streamlit: Web-based UI for model interaction
  - Scikit-learn: Feature encoding & scaling
  - TensorFlow/Keras: Model training and inference
  - Pandas/Numpy: Data manipulation
 
💡 Future Improvements

- Enhance model accuracy with additional features
- Deploy as a REST API for better scalability
- Improve UI with interactive visualizations

🤝 Contributing

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

📜 License

This project is licensed under the MIT License.

🌟 Don't forget to star ⭐ the repository if you find it useful!

Happy coding! 😊





