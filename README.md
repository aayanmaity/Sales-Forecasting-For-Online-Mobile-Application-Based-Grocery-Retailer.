# Sales-Forecasting-For-Online-Mobile-Application-Based-Grocery-Retailer.

Forecasting unit sales for a huge online/mobile application-based grocery
retailer, across several locations and product categories. Using the past 4 years data and 3 other domain-related datasets, handled
high cardinal categorical variable with `categorical embeddings` using deep learning, generated non-linear features using
`autoencoders`, built a `regression-based model` using boosting tree method.

![Alt Text](https://github.com/aayanmaity/Sales-Forecasting-For-Online-Mobile-Application-Based-Grocery-Retailer./blob/main/Report/nrd-D6Tu_L3chLE-unsplash.jpg)

## Project Details.

Small Basket is a huge online / mobile application-based grocery retailer in India, founded
in 2011. Small Basket is trying to manage its supply chain and delivery partners and would
like to accurately forecast the sales for the period starting from January of 2019 to August
of 2019. 
In this project, we are tasked with creating a model that can accurately forecast the
sales for small basket across several locations and product categories.

## Dataset Description:

There are 5 datasets along with a sample submission file provided to you in this
competition. The datasets are named as follows and have the following attributes:

`train.csv`:
*  **date:** The sales measured during a particular day.
*  **location_id:** The location from where the sold units were dispatched.
*  **item_id:** The identifier of a product that was sold.
*  **unit_sales:** The number of sales of a particular item from a particular location at the given date.
*  **onpromotion:** Whether the given product was sold in a promotion or a discount.

`train_transactions.csv`:
* **date:** The day during which the number of transactions are measured (Only given for the duration of the ‘train.csv’ file).
* **location_identifier (location_id in train.csv):** The location from where the transactions were handled.
* **transactions:** The number of transactions handled by the particular location.

`items.csv`:
* **item_id:** An identifier of a product
* **category_of_item:** The category to which the product belongs to
* **class:** Another way to categorize the product (Provided by the Business Intelligence Team)
* **perishable:** Whether the item is perishable or not.

`locations.csv`:
* **location_id:** The location of the store / warehouse (unit)
* **city:** The city where the unit is located
* **state:** The state in which the city is located
* **type:** The type of business unit (‘A’, ‘B’, ‘C’, ‘D’, ‘E’)
* **cluster:** The cluster that the unit belongs to (Provided by the Business Intelligence team)

`test.csv`:
*  **id**: id
*  **date:** The sales measured during a particular day.
*  **location_id:** The location from where the sold units were dispatched.
*  **item_id:** The identifier of a product that was sold.
*  **onpromotion:** Whether the given product was sold in a promotion or a discount.


## Tools used:

**Code:** Python Version: 3.7

**For data wrangling and visualization:** NumPy, Pandas, Matplotlib, Seaborn

**For predictive analytics:** scikit-learn, LightGBM, Tensorflow, Keras

**For Reporting:** Google Slides

## Tasks:

* Exploring the data and engineer new features.

* Predicting the number of sales for a given item for the dates given in the `test.csv` file.

## Answering Operation Team Questions:

* Business units belonging to which cluster will see the highest amount of sales in 2019?
* What are the top 10 selling items in this cluster?
* What is the rate of purchase per week for these items?

## Reports

Sales Forecasting For Small Basket 
