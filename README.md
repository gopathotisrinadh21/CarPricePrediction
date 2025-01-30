# Car Price Prediction

## Overview
The **Car Price Prediction** project is a machine learning model that predicts the price of a car based on various features such as fuel type, gear type, model, and kilometers driven. The model is built using **Multi-Linear Regression**.

## Features
- Predicts car prices based on input parameters
- Uses **Multi-Linear Regression** for model training
- Developed with **Python** and **Flask** for deployment
- Dataset preprocessed for optimal predictions

## Tech Stack
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Framework:** Flask (for deployment)
- **Tools:** Jupyter Notebook, Google Colab

## Dataset
The dataset contains the following columns:
- **Car Model:** The make and model of the car
- **Fuel Type:** Petrol/Diesel/Electric
- **Gear Type:** Manual/Automatic
- **Kilometers Driven:** Distance the car has traveled
- **Selling Price:** Target variable (car price to be predicted)

## Model Building
1. **Data Preprocessing:**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
2. **Model Training:**
   - Splitting data into training and testing sets
   - Applying Multi-Linear Regression
   - Evaluating model performance using R-squared and RMSE

## Installation & Usage
### Prerequisites
Make sure you have Python installed along with the required libraries.
```bash
pip install pandas numpy scikit-learn flask matplotlib seaborn
```

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/car-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd car-price-prediction
   ```
3. Run the Jupyter Notebook to train the model:
   ```bash
   jupyter notebook
   ```
4. Start the Flask server:
   ```bash
   python app.py
   ```
5. Open your browser and go to `http://127.0.0.1:5000/` to access the web app.

## Results & Performance
- Achieved **high accuracy** with Multi-Linear Regression
- Visualized feature importance and residual errors

## Future Improvements
- Adding more features like brand reputation, car age, and location
- Implementing other regression models for better accuracy
- Deploying the model using cloud services like AWS or Heroku

## Contributors
- **Srinadh** - Developer

## License
This project is licensed under the MIT License.

