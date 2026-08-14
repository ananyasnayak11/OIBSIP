# Customer Segmentation

## OASIS INFOBYTE Data Analytics Internship

### Level 1 - Task 2

## Objective

The objective of this project is to segment customers based on their
purchasing behaviour using RFM analysis and K-Means clustering.

## Dataset

The project uses the Online Retail Dataset obtained from Kaggle.
The dataset contains transaction details such as invoice number,
product information, quantity, price, customer ID, date and country.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Data Preprocessing

- Loaded the Online Retail dataset
- Checked the dataset structure
- Handled missing Customer IDs
- Removed cancelled transactions
- Removed invalid quantity and price values
- Removed duplicate records
- Calculated total transaction amount

## RFM Analysis

Customer behaviour was analyzed using three RFM features:

- Recency - How recently a customer made a purchase
- Frequency - How often a customer made purchases
- Monetary - How much a customer spent

## Customer Segmentation

K-Means clustering was applied to the RFM features to divide customers
into different groups based on their purchasing behaviour.

The Elbow Method was used to help determine the appropriate number
of clusters.

## Visualizations

The project includes visualizations for:

- Elbow Method
- Customer clusters
- RFM analysis
- Customer behaviour

## Results

The clustering analysis identified different customer groups based on
their purchasing patterns. These segments can help businesses
understand customer behaviour and develop targeted marketing strategies.

## Conclusion

Customer segmentation using RFM analysis and K-Means clustering provides
useful insights into customer purchasing behaviour. The identified
customer groups can be used to improve customer targeting, marketing
strategies and customer relationship management.
