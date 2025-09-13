**Classification project:**

**Objective**-The classification goal is to predict if the client will subscribe a term deposit or not.

**Description**
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required,in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 

**Target variable**
('Y') has or hasn't subscribe to term deposite or no features: job, marital, education, default, housing, loan , contact, month, poutcome, age, balance, day, campaign, pdays, previous, duration. 

**DATA**-The data consists of 17 attributes.

**Exploratory Data Analysis (EDA**): 
Line Plots,Scatter Plots,Histograms,Pairplots,Correlation Heatmap.

**Data preprocessing**

Identified unique values for each column.
No missing values were found.
Treated outliers using IQR method and validated with Boxplot.
Ensured target variable was properly filled before modeling.
Converted object datatype into numeric datatype .

**Conclusion**

 In conclusion RandomForest Classifier and ANN is the best fit for the datasetDropped unnecessary columns .
      
**FUTURE INSIGHTS**

Improve interpretability using SHAP/LIME.
Deploy as a web app/API for real-time predictions.
Use customer segmentation for targeted campaigns.
Test on larger, updated datasets for scalability.

