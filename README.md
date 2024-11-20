# COS781 Data Mining Project

This project provides a comprehensive analysis of customer reordering behavior using the **Instacart Market Basket** dataset. It compares two advanced machine learning approaches:  
1. **Neural Collaborative Filtering (NCF)** with **Adam optimization**  
2. **XGBoost**

## Run Instructions

1. **Download the Dataset**  
   Obtain the dataset from [Kaggle's Instacart Market Basket Analysis competition](https://www.kaggle.com/c/instacart-market-basket-analysis).

2. **Extract the Dataset**  
   After downloading, extract the dataset into a folder on your system.

3. **Organize the Files**  
   Create a new folder and move the following dataset files into it:
   - `aisle.csv`
   - `department.csv`
   - `order_products__prior.csv`
   - `order_products__train.csv`
   - `orders.csv`
   - `products.csv`
   - `sample_submission.csv`

4. **Download the Notebook**  
   Download the Jupyter Notebook file `market_analysis_final.ipynb` from this GitHub repository and place it in the same folder with the dataset files.

   Your folder structure should look like this:

   ```text
   Folder (Newly created folder)
   ├── market_analysis_final.ipynb
   ├── aisle.csv
   ├── department.csv
   ├── order_products__prior.csv
   ├── order_products__train.csv
   ├── orders.csv
   ├── products.csv
   ├── sample_submission.csv

     
  5. **Run the Notebook**
     Open the Jupyter Notebook file (market_analysis_final.ipynb) and execute all the cells using the menu option Cell > Run All.

  6. **View Notebook Outputs on GitHub**
     Alternatively, you can view the executed notebook directly in this repository. Click on the file market_analysis_final.ipynb to see the outputs displayed in the GitHub interface.
