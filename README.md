# House Price Prediction Using Scikit 🏡💰

This project uses machine learning techniques to predict house prices based on various features such as location, square footage, number of bedrooms, and more. It employs Scikit-learn for model training, testing, and evaluation. 

## Prerequisites 📋

Before using this repository, ensure you have the following:

- Python 3.x 🐍
- Scikit-learn 📚
- Pandas 🍑
- Numpy ➗
- Matplotlib 📈

## Installation ⚙️

1. Clone this repository:

   ```bash
   git clone https://github.com/sujalbafna/House-Price-Prediction-Using-Scikit.git
   ```

2. Navigate to the project directory:

   ```bash
   cd House-Price-Prediction-Using-Scikit
   ```

3. Install the necessary dependencies:

   ```bash
   pip install -r requirements.txt
   ```

   Or manually install the dependencies:

   ```bash
   pip install scikit-learn pandas numpy matplotlib
   ```

## Usage 🚀

### Step 1: Prepare the Data 📂

- The dataset is located in the `data/` folder. You can modify the dataset or replace it with your own if necessary.

### Step 2: Train the Model 🧑‍🏫

1. Open the `train_model.py` file.
2. The script will load the dataset, preprocess the features, and train a regression model to predict house prices.
3. You can choose the regression model you want to use (e.g., Linear Regression, Decision Tree, etc.) in the script.

To run the model training:

```bash
python train_model.py
```

This will train the model and save the trained model to a file.

### Step 3: Test the Model ✅

1. Open the `test_model.py` file to test the model with new house data.
2. Replace `new_house_data` with the features of a house for prediction.

To test the model:

```bash
python test_model.py
```

This will predict the house price based on the given features.

### Step 4: Evaluate the Model 📊

The model’s performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score, which are printed after training.

## Example Usage 💡

```python
# Example of predicting a house price
house_data = [3, 2, 1500, 200000]  # [bedrooms, bathrooms, square footage, location_index]
predicted_price = model.predict([house_data])
print(predicted_price)  # Output: Predicted price of the house
```

## Folder Structure 📂

- `data/` – Contains the dataset for training and testing.
- `train_model.py` – Script for training the model.
- `test_model.py` – Script for testing the model.
- `requirements.txt` – List of required libraries.

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

- Scikit-learn documentation for the machine learning models and tools.
- [Other resources you used].
```
