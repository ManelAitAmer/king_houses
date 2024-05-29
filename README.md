# king_houses
![presentation-economy-02](https://github.com/ManelAitAmer/king_houses/assets/160795377/2619d471-a1ae-44cd-8c69-9edc11c96c03)

## What is it about?

Our mission is to delve into a dataset of house sale prices for King County, including Seattle, spanning one year from May 2014 to May 2015. This project encompasses various computational tasks such as data loading, visualization, calculating returns, and portfolio analysis, tailored to the real estate domain.

## Our Data: 

features 21 different columns, providing a comprehensive overview of the real estate market:

***id:***  A unique identifier for a house.

***date:*** The date on which the house was sold.

***price:*** The sale price of the house (prediction target).

***bedrooms:*** Number of bedrooms in the house.

***bathrooms:*** Number of bathrooms in the house, per bedroom.

***sqft_living:*** Square footage of the interior living space.

***sqft_lot:*** Square footage of the land space.

***floors:*** Number of floors (levels) in the house.

***waterfront:*** Whether the house has a waterfront view.

***view:*** Number of times the house has been viewed.

***condition:*** The overall condition of the house.

***grade:*** The overall grade given to the house, based on the King County grading system.

***sqft_above:*** Square footage of the house apart from the basement.

***sqft_basement:*** Square footage of the basement.

***yr_built:*** The year the house was built.

***yr_renovated:*** The year the house was renovated.

***zipcode:*** ZIP code area.

***lat:*** Latitude coordinate.

***long:*** Longitude coordinate.

***sqft_living15:*** The interior living space for the nearest 15 neighbors in 2015.

***sqft_lot15:*** The land spaces for the nearest 15 neighbors in 2015.

***TARGET --> Price:*** Our primary focus is to understand which features most significantly impact the house price. Additionally, we aim to explore properties valued at $650K and above for more detailed insights.

## Data Preprocessing :card_index_dividers: :

Here we will split our data in X and y. 

* In X we have all the columns except the target column (price) , and y has only the target column.
* The model we chosed is 70% - 30%.
* 100% of our data: 21613.
* 70% for training data: 15129.
* 30% for test data: 6484.
  
We selected different models, to finally chose the one that that improved the model better and that has best result .

***So the models we used are:***

* LinearRegression.
* Ridge regression.
* Lasso regression.
* Decision Tree regression.
* KNN regression.
* XGBoost Regression.
<img width="629" alt="Screenshot 2024-05-23 at 15 51 40" src="https://github.com/ManelAitAmer/king_houses/assets/160795377/0d15e7cb-f112-466d-a419-293096dba723">

<code style="color : yellowgreen">The model we are chosing is the Decision Tree regression.</code> 

