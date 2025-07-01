# Zomato-Data-Analysis

This project analyzes restaurant data from Zomato to uncover insights about restaurant types, ratings, online ordering trends, and customer preferences.

## Dataset

- **File:** [Zomato_dataset.csv](Zomato_dataset.csv)
- Contains restaurant details such as name, online order availability, table booking, ratings, votes, cost for two, and type.

## Analysis

The analysis is performed in the Jupyter notebook [Zomato_analysis.ipynb](Zomato_analysis.ipynb) using Python libraries:
- pandas
- numpy
- matplotlib
- seaborn

### Key Steps

1. **Data Loading & Cleaning:**  
   Load the dataset and preprocess columns (e.g., convert ratings to float).

2. **Exploratory Data Analysis:**  
   - Distribution of restaurant types  
   - Total votes per restaurant type  
   - Ratings distribution  
   - Cost analysis  
   - Relationship between online ordering and ratings  
   - Heatmap of online order availability by restaurant type

3. **Visualization:**  
   Various plots (countplot, histogram, boxplot, heatmap) are used to visualize the data.

### Conclusion

- Dining restaurants primarily accept offline orders, whereas cafes primarily receive online orders.
- Clients prefer to place orders in person at restaurants, but prefer online ordering at cafes.

## Usage

1. Clone the repository or download the files.
2. Install required libraries:
   ```sh
   pip install pandas numpy matplotlib seaborn