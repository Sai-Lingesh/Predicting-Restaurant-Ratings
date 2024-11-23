# Restaurant Rating Prediction Application

Welcome to the **Restaurant Rating Prediction** project! This repository contains the code and implementation for predicting restaurant ratings based on specific input features using a machine learning model. The project is built with Python and Streamlit, and it includes a Jupyter Notebook for model creation and a Streamlit app for deployment.

---

## Features

1. **Prediction Application**:
   - Input fields for:
     - Average cost for two
     - Table booking availability
     - Online delivery availability
     - Price range (1 to 4)
   - Displays restaurant ratings in categories such as:
     - Poor
     - Average
     - Good
     - Very Good
     - Excellent

2. **Interactive UI**:
   - Built with Streamlit for a user-friendly experience.
   - Includes visual effects like snow animations.

3. **Machine Learning Integration**:
   - Utilizes a pre-trained machine learning model (`mlmodel.pkl`).
   - Scales input features using a pre-saved scaler (`Scaler.pkl`).

4. **Jupyter Notebook**:
   - Contains the data exploration, preprocessing, and model training steps.
   - Offers insights into the methodology and performance of the predictive model.

---

## File Structure

- **`app.py`**: Main Streamlit application file for the prediction interface.
- **`Predicting Restaurant Ratings.ipynb`**: Jupyter Notebook for model development.
- **`Scaler.pkl`**: Pre-trained scaler used for feature normalization (not included in this repository).
- **`mlmodel.pkl`**: Machine learning model file for predictions (not included in this repository).

---

## Installation and Usage

### Prerequisites
- Python 3.8 or above
- Libraries: `streamlit`, `numpy`, `joblib`, `sklearn`

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url
   cd your-repo-directory
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

4. Open the browser and use the interactive interface to predict restaurant ratings.

---

## Inputs for Prediction
- **Average Cost for Two**: A numeric value (50 to 999999).
- **Table Booking Availability**: Dropdown option (Yes/No).
- **Online Delivery Availability**: Dropdown option (Yes/No).
- **Price Range**: Dropdown option (1 to 4).

---

## Output Categories
The application predicts restaurant ratings in the following categories:
- Poor
- Average
- Good
- Very Good
- Excellent

---

## Author
**Sai Lingesh R**  
- LinkedIn: [Sai Lingesh](https://www.linkedin.com/in/sai-lingesh)

---

## Acknowledgments
This project is a demonstration of machine learning and Streamlit capabilities in providing predictive analytics for restaurant ratings.
