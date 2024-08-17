# California House Pricing Prediction

This project aims to predict the median house prices in California using various features such as geographical location, population, and housing statistics. The project is implemented in Python using popular data science libraries like Pandas, NumPy, Scikit-learn, and Seaborn.

## Project Structure

- **`house pricing.ipynb`**: The main Jupyter notebook containing all the code for data preprocessing, exploratory data analysis, and model training.
- **`archive/housing.csv`**: The dataset used in this project. It contains various features related to house prices in different regions of California.

## Dataset

The dataset used in this project includes the following features:
- `longitude`: Longitude of the region.
- `latitude`: Latitude of the region.
- `housing_median_age`: Median age of the houses in the region.
- `total_rooms`: Total number of rooms in the region.
- `total_bedrooms`: Total number of bedrooms in the region.
- `population`: Population of the region.
- `households`: Number of households in the region.
- `median_income`: Median income of the households in the region.
- `median_house_value`: Median house value in the region (target variable).

## Steps Involved

1. **Data Loading and Cleaning**:
   - Load the dataset using Pandas.
   - Handle missing values by removing rows with any null values.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize relationships between features using Matplotlib and Seaborn.
   - Understand the distribution and correlations within the data.

3. **Data Splitting**:
   - Split the data into training and testing sets using Scikit-learn’s `train_test_split`.

4. **Model Training**:
   - Train various machine learning models to predict house prices.
   - Evaluate model performance using appropriate metrics.

## How to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/california-house-pricing.git
   cd california-house-pricing
   ```

2. **Install Dependencies**:
   Ensure you have Python installed, then install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   Open the Jupyter notebook to execute the code:
   ```bash
   jupyter notebook house\ pricing.ipynb
   ```

## Results

The notebook will guide you through the process of data preprocessing, visualization, and model training. The final section of the notebook will showcase the model’s performance in predicting house prices based on the test set.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

You can install all dependencies via:
```bash
pip install -r requirements.txt
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
