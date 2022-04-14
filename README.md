# Philadelphia-Housing

**Project Title**: Philadelphia Housing and Property Value Investigation  
Team Members: Shusaku Asai, Congjun Huang, Jingjing Wang   

#### Project Description     
Many machine learning applications model home sales price. We extended this work by applying various 
sales price models to Single-Family, Multi-Family, Mixed-Use, Industrial, Commercial, and Vacant Land
property types in Philadelphia. Within each property type, we built and tuned a best performing model and 
tested its generalizability on future unseen data. We found that the Single-Family property type model had 
the best performing model on the test data and the Commercial property type had the worst performing 
model as defined by RMSE. Across all property types, XGBoost and Random Forest models showed 
superior performance. Future home buyers in Philadelphia may find our model useful in predicting sales 
prices of homes. Government and businesses should use the Commercial, Industrial, Mixed-Use and Vacant 
Land models with caution due to their poorer generalizability.


<ins>The project is visualized with the below flowchart:</ins> 
  
     
     
     
![image](https://user-images.githubusercontent.com/53063128/163472517-5cb10293-d1dd-4380-9366-a234b3097f6c.png)   


Code for each respective part of the flowchart can be found in the following directories in our GitHub page:   

### Processing:    

https://github.com/delashu/Philadelphia-Housing/tree/main/processing

### Exploratory Analyses & Viz:   
https://github.com/delashu/Philadelphia-Housing/tree/main/EDA

### Modeling: 

https://github.com/delashu/Philadelphia-Housing/tree/main/model
