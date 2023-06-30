
# Customer-Behavior-Prediction-XGBoost-EDA
- This repository contains the code and data for a project on Customer Buying Behavior prediction. The project uses the marketing_campaign.csv dataset, which can be downloaded from Kaggle:https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign


## Data Source

- A response model can provide a significant boost to the efficiency of a marketing campaign by increasing responses or reducing expenses. The objective is to predict who will respond to an offer for a product or service.
The columns are:

- Response (target) - 1 if customer accepted the offer in the last campaign, 0 otherwise
- Complain - 1 if customer complained in the last 2 years
- DtCustomer - date of customer’s enrolment with the company
- Education - customer’s level of education
- Marital - customer’s marital status
- Kidhome - number of small children in customer’s household
- Teenhome - number of teenagers in customer’s household
- Income - customer’s yearly household income
- MntFishProducts - amount spent on fish products in the last 2 years
- MntMeatProducts - amount spent on meat products in the last 2 years
- MntFruits - amount spent on fruits products in the last 2 years
- MntSweetProducts - amount spent on sweet products in the last 2 years
- MntWines - amount spent on wine products in the last 2 years
- MntGoldProds - amount spent on gold products in the last 2 years
- NumDealsPurchases - number of purchases made with discount
- NumCatalogPurchases - number of purchases made using catalogue
- NumStorePurchases - number of purchases made directly in stores
- NumWebPurchases - number of purchases made through company’s web site
- NumWebVisitsMonth - number of visits to company’s web site in the last month
- Recency - number of days since the last purchase
## Installation
The following tools were used for this analysis:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Sklearn
- ydata_profiling
- XGBClassifier

- To run this project, you will need to have Python 3 installed on your machine. You can install the required libraries by running the following command:


- pip install pandas matplotlib seaborn numpy plotly ydata_profiling XGBClassifier

    
## Usage 
- To run the analysis, simply execute the notebook. The script will generate several visualizations that help illustrate analysis of data.
## Roadmap

The analysis includes the following tasks:

- Data loading and cleaning
- Exploratory data analysis
- Feature engineering
- Correlation analysis
- detecting outliers
- preprocessing 
- building model
- evaluating model
- visualization results

The analysis includes visualizations using Matplotlib, Plotly and Seaborn.

## Contributing

- Contributions to this project are welcome. If you notice any errors or have ideas for additional analyses, please feel free to open an issue or submit a pull request.


## Conclusion 
* In This Project, I build a Model of market campaign prediction using XGBoost algorithm after evaluated different algorithms to trained and evaluation the model. Overall, the use of XGBoost in a market campaign holds tremendous potential for organizations to gain a competitive edge, improve marketing effectiveness, and enhance customer experiences. And Evaluate the Accuracy of this model. The accuracy score is 85.49%.