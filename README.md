# Techvolt-Intern

***Day_1_&_2_***
  Python basics

***Day_3***
  Linear Regression

***Day_4***
  Lasso and Ridge Regression

***Day_5***
  K nearest neighbors with Python

***Day_6***
  Titanic data analysis - Logistic Regression

***Day_7***
  Naive Bayes - Adult dataset
  
 ***Assignment_1***
 
 Consider a data set (Train.csv and Test.csv) related to sales of items in shops. The fields in Train.csv data set are:

    Item_Identifier: Code given to items

    Item_Weight: Weight of an item

    Item_Fat_Content: Fat content of the item like low, high etc

    Item_Visibility: A continuous value indicating the visibility of the item for a customer

    Item_Type: Type of the item like dairy, vegetables etc

    Item_MRP: Maximum retail price of the item

    Outlet_Identifier: Code given to outlets

    Outlet_Establishment_Year : Year of establishment of an outlet

    Outlet_Size: Size of an outlet like medium, high etc.

    Outlet_Location_Type: Location of the outlet in a city like Tier1, 2 etc.

    Outlet_Type: Type of the outlet like supermarket, grocery shop etc.

    Item_Outlet_Sales: Sale value of an item in outlet. It is a target variable.

    The Test.csv do not contain the field Item_Outlet_Sales.

Tasks:
  Use the Train.csv file for fitting the models (Divide this file into training set and testing set)
  Treat the missing values appropriately
  Convert the categorical data into numerical data appropriately, if necessary.
  Normalize the data, if required.
  Fit linear regression model and compute RMSE and R-Square.
  Apply regularization techniques on the data to check whether they are better than the basic linear model. Loop through various regularization parameters to display and compare R-Square.
  Fit the residual plots in all cases.
  Give your analysis on which of the independent variables have significant impact on the Sales of an outlet. Call it as a best model.
  Using this best model, predict the values of sales for the data given in the file Test.csv and compute RMSE and R-Square.

NOTE:
  Give brief explanation about each task that you are going to do.
  Draw Graphs where and when required and give interpretation of such graphs.
  Graphs must have proper labels and legends. 
  At the end of task, give your analysis on the entire dataset, about features, their importance etc.

***Day_8 (Task)***

  Bob has started his own mobile company. He wants to give tough fight to big companies like Apple,Samsung etc.
  He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.
  Bob wants to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price. But he is not so good at Machine Learning. So he needs your help to solve this problem.
  In this problem you do not have to predict actual price but a price range indicating how high the price is.
 
In this data:

    id:ID

    battery_power:Total energy a battery can store in one time measured in mAh

    blue:Has bluetooth or not

    clock_speed:speed at which microprocessor executes instructions

    dual_sim:Has dual sim support or not

    fc:Front Camera mega pixels

    four_g:Has 4G or not

    int_memory:Internal Memory in Gigabytes

    m_dep:Mobile Depth in cm

    mobile_wt:Weight of mobile phone

    n_cores:Number of cores of processor

    pc:Primary Camera mega pixels

    px_height:Pixel Resolution Height

    px_width:Pixel Resolution Width

    ram:Random Access Memory in Megabytes

    sc_h:Screen Height of mobile in cm

    sc_w:Screen Width of mobile in cm

    talk_time:longest time that a single battery charge will last when you are

    three_g:Has 3G or not

    touch_screen:Has touch screen or not

    wifi:Has wifi or not

***Day_9***
  SVM Implementation


***Day_10***
  Decision Tree

***Day_11***
  Random Forest
  
  
  Task_2

***Day_12***
  Adaboost

***Day_13***
  Task_3
  
  Assignment_2
  
  
  *Predict Loan Eligibility for Dream Housing Finance company*
      Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.
      Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers.

  *Data Dictionary*
    Train file: CSV containing the customers for whom loan eligibility is known as 'Loan_Status'
    
    Loan_ID
      Unique Loan ID
    Gender
      Male/ Female
    Married
      Applicant married (Y/N)
    Dependents
      Number of dependents
    Education
      Applicant Education (Graduate/ Under Graduate)
    Self_Employed
      Self employed (Y/N)
    ApplicantIncome
      Applicant income
    CoapplicantIncome
      Coapplicant income
    LoanAmount
      Loan amount in thousands
    Loan_Amount_Term
      Term of loan in months
    Credit_History
      credit history meets guidelines
    Property_Area
      Urban/ Semi Urban/ Rural
    Loan_Status
      (Target) Loan approved (Y/N)
 
    Test file: CSV containing the customer information for whom loan eligibility is to be predicted

    Loan_ID
      Unique Loan ID
    Gender
      Male/ Female
    Married
      Applicant married (Y/N)
    Dependents
      Number of dependents
    Education
      Applicant Education (Graduate/ Under Graduate)
    Self_Employed
      Self employed (Y/N)
    ApplicantIncome
      Applicant income
    CoapplicantIncome
      Coapplicant income
    LoanAmount
      Loan amount in thousands
    Loan_Amount_Term
      Term of loan in months
    Credit_History
      credit history meets guidelines
    Property_Area
      Urban/ Semi Urban/ Rural

***Final Assessment***
  Predict Number of Upvotes

   An online question and answer platform has hired you as a data scientist to identify the best question authors on the platform. This identification will bring more insight into increasing the user engagement. Given the tag of the question, number of views received, number of answers, username and reputation of the question author, the problem requires you to predict the upvote count that the question will receive.
  
  Data Dictionary

    ID - Question ID
    Tag - Anonymised tags representing question category
    Reputation - Reputation score of question author
    Answers - Number of times question has been answered
    Username - Anonymised user id of question author
    Views - Number of times question has been viewed
    Upvotes - (Target) Number of upvotes for the question
  
  Evaluation Metric
  The evaluation metric is RMSE (root mean squared error)
