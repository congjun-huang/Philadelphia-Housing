# Philadelphia-Housing

### Project Title: Investigation of Property Sale Prices Using Machine Learning in Philadelphia 
Team Members: Shusaku Asai, Congjun Huang, Jingjing Wang   

### Project Description     
Many machine learning applications model home sales price. We extended this work by applying various 
sales price models to Single-Family, Multi-Family, Mixed-Use, Industrial, Commercial, and Vacant Land
property types in Philadelphia. Within each property type, we built and tuned a best performing model and 
tested its generalizability on future unseen data. We found that the Single-Family property type model had 
the best performing model on the test data and the Commercial property type had the worst performing 
model as defined by RMSE. Across all property types, XGBoost and Random Forest models showed 
superior performance. Future home buyers in Philadelphia may find our model useful in predicting sales 
prices of homes. Government and businesses should use the Commercial, Industrial, Mixed-Use and Vacant 
Land models with caution due to their poorer generalizability.

### Data
We utilized the publicly available Philadelphia Properties and Assessment History dataset. Data source and data dictionary can be found below.
#### Data Source:

https://opendata-downloads.s3.amazonaws.com/opa_properties_public.csv

#### Data Dictionary:

https://metadata.phila.gov/#home/datasetdetails/5543865f20583086178c4ee5/representationdetails/55d624fdad35c7e854cb21a4/?view_287_page=1

### Experimental Design
<ins>The project is visualized with the below flowchart:</ins> 
  
     
     
     
![image](https://user-images.githubusercontent.com/53063128/163472517-5cb10293-d1dd-4380-9366-a234b3097f6c.png)   

### Conclusions
The Single-Family property type model had the smallest test RMSE and thus had best generalizability for 
future predictions. Commercial property type model had the largest test RMSE, and thus had the worst 
generalizability. The XGBoost and Random Forest models were superior in both validations set and 
generalizability.\
Our Single-Family and Multi-Family models show utility that future home buyers in Philadelphia may find 
useful. By training a model with all available data, a user may input a desired home’s amenities and location 
to predict the sale price. Government organizations and private companies in Philadelphia may find our 
model for Mixed, Vacant, Commercial, and Industrial useful, but we recommend this be done with caution 
due to the larger test RMSE and poorer generalizability.\
The poor generalizability of the Commercial and Industrial property types may be a result of the underlying 
variability of price and smaller data availability. The superior performance of the Single-Family type in 
contrast may be due to a larger and more robust sample size and tighter distribution in sale price. Future 
works that aim to predict Commercial and Industrial property types should ensure a generally non-missing 
feature space or attempt to aggregate datapoints from several cities to increase sample size. 

### User Instructions
#### Step 1: Clone the GitHub repository
   

#### Step 2: Create a virtual environment for the project 

#### Step 3: Install necessary packages

#### Step 4: Get data
##### Data Source:
https://opendata-downloads.s3.amazonaws.com/opa_properties_public.csv
##### Data Dictionary:
https://metadata.phila.gov/#home/datasetdetails/5543865f20583086178c4ee5/representationdetails/55d624fdad35c7e854cb21a4/?view_287_page=1

#### Step 5: Run the code
All the experiment results can be accessed through the following 3 parts of code.
##### Exploratory Data Analysis & Visualization:   

https://github.com/delashu/Philadelphia-Housing/tree/main/EDA

##### Processing:    

https://github.com/delashu/Philadelphia-Housing/tree/main/processing

##### Modeling: 

https://github.com/delashu/Philadelphia-Housing/tree/main/model

#### Step 6: Check the video
##### Video:

https://www.youtube.com/watch?v=Zv0nwZJKiHA



