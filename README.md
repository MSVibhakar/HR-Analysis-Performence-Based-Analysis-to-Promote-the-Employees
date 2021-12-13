# HR-Analysis-Performence-Based-Analysis-to-Promote-the-Employees
HR analytics is revolutionising the way human resources departments operate, leading to higher efficiency and better results overall. Human resources has been using analytics for years. However, the collection, processing and analysis of data has been largely manual, and given the nature of human resources dynamics and HR KPIs, the approach has been constraining HR. Therefore, it is surprising that HR departments woke up to the utility of machine learning so late in the game.
* Source fo the data is taken from the Analytics Vidya platform 
* Problem Statment :
Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:
They first identify a set of employees based on recommendations/ past performance
Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles.
Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle.


* We have follwed a approch to make the f1 scores better in the model , we have used logistic regression and XBboost and Random forest calssifers :
* The F1 scores intially are :
* <img width="312" alt="image" src="https://user-images.githubusercontent.com/85379601/145749544-108ec5bc-8540-40f2-bc6c-c627f730c071.png">

In the intial approach we have filled null values with the mode and meadian which did not have a good F1 scores but later we have follwed and logical method 
and used ffill and bfill which gave promissing results .
Hyper parameter is done for XGBoost , but the initial results showed the promissig results 
 
