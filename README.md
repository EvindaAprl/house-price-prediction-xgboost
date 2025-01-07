# House Price Prediction with XGBoost
This project implements a machine learning model using XGBoost to predict house prices. It utilizes a gradient boosting approach for regression tasks.

## Installation
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/EvindaAprl/house-price-prediction-xgboost.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd house-price-prediction-xgboost
    ```
3.  **Create a virtual environment (recommended):**
    *   It is highly recommended to use a virtual environment to isolate project dependencies.
    ```bash
    python -m venv venv
    ```
    *   **Activate the virtual environment:**
        *   **Linux/macOS:**
            ```bash
            source venv/bin/activate
            ```
        *   **Windows:**
            ```bash
            venv\Scripts\activate
            ```
4.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Data
* The dataset should be located at `./data/jabodetabek_house_price.csv`

## Model and Transformation
* Model file will be saved at `model/xgboost_model.pkl` if you train your own model.
* The trained `PowerTransformer` object for preprocessing data is saved as `transform/transform.pkl`

## Contributing
Please feel free to create a pull request if you want to contribute to this project.
