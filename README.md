Medical Insurance Claim Prediction System

Overview

The Medical Insurance Claim Prediction System is a machine learning project that predicts the medical insurance charges of an individual based on various factors such as age, gender, BMI, number of children, smoking status, and region. The project helps insurance companies and customers estimate healthcare expenses accurately.

Features

- Data preprocessing and analysis
- Insurance charge prediction using Machine Learning
- User-friendly prediction system
- Model training and evaluation
- Accurate and efficient results

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- VS Code

Dataset

The dataset contains the following attributes:

- Age
- Sex
- BMI
- Number of Children
- Smoker Status
- Region
- Charges (Target Variable)

Project Structure

Medical_Insurance_Claim_Prediction/
│
├── insurance.csv
├── train_model.py
├── insurance_prediction.py
├── model.pkl
├── requirements.txt
└── README.md

Installation

1. Clone the Repository

git clone <repository_url>

2. Install Required Libraries

pip install -r requirements.txt

3. Train the Model

python train_model.py

4. Run the Prediction Program

python insurance_prediction.py

Machine Learning Algorithm

This project uses the Linear Regression algorithm to predict medical insurance claim amounts.

Workflow

1. Load the dataset.
2. Preprocess the data.
3. Train the machine learning model.
4. Save the trained model.
5. Predict insurance claim amounts based on user input.

Output

The system takes user information as input and predicts the estimated medical insurance charges.

Example:

Enter age: 25
Enter sex (0-Female, 1-Male): 1
Enter BMI: 24.5
Enter number of children: 1
Enter smoker status (0-No, 1-Yes): 0
Enter region: 2

Predicted Insurance Charges: ₹18,500

Applications

- Health Insurance Companies
- Healthcare Organizations
- Risk Assessment
- Policy Planning

Future Enhancements

- Web-based interface
- Advanced machine learning models
- Real-time prediction system
- Improved accuracy with larger datasets

Author

Developed as a Machine Learning project using Python and Scikit-learn.
