# Insurance Cost Prediction

A machine learning project contained entirely within a single Jupyter Notebook. The notebook covers data loading, exploratory data analysis (EDA), data preprocessing, feature engineering, model training, and performance evaluation to predict personal medical insurance costs based on individual demographic and health attributes.

---

## Key Features

* **Exploratory Data Analysis (EDA):** Visualizations analyzing feature distributions and correlations between user attributes (e.g., age, BMI, smoker status) and insurance charges.
* **Data Preprocessing:** Handles categorical encoding (e.g., region, sex, smoker status) and numerical feature scaling.
* **Model Training & Evaluation:** Trains and compares regression models (e.g., Linear Regression, Decision Tree, Random Forest) using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and $R^2$ Score.

---

## Tech Stack

* **Language:** Python 3.10+
* **Environment:** Jupyter Notebook / Google Colab
* **Libraries:**
  * **Data Manipulation:** Pandas, NumPy
  * **Visualization:** Matplotlib, Seaborn
  * **Machine Learning:** scikit-learn

---

## Dataset Attributes

The notebook predicts insurance charges using the following feature inputs:

* `age`: Age of the primary beneficiary
* `sex`: Gender of the policyholder (`female`, `male`)
* `bmi`: Body Mass Index ($kg/m^2$)
* `children`: Number of children/dependents covered by health insurance
* `smoker`: Smoking status (`yes`, `no`)
* `region`: Beneficiary's residential area in the US (`northeast`, `southeast`, `southwest`, `northwest`)
* **Target variable:** `charges`: Individual medical costs billed by health insurance

---

## Getting Started

### 1. Prerequisites & Installation

Clone the repository and install the required dependencies:

```bash
git clone [https://github.com/your-username/InsurancePrediction.git](https://github.com/your-username/InsurancePrediction.git)
cd InsurancePrediction

# Create virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: .\venv\Scripts\activate

# Install dependencies
pip install jupyter pandas numpy matplotlib seaborn scikit-learn
