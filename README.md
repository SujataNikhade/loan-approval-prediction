# INTRODUCTION
A loan approval prediction project comes to deciding whether the applicants profile is relevant to be granted with loan or not.
# GOAL
To develop a ML model can predict whether a loan application will be approved or reject based on various attributes of the appicant,like income ,Credit score,employment history and other information.For faster and more informed loan eligibility while minimizing risks of defaulting loans.
# parameters
loan id- in the loan id ineach person contain there unique id 
credit history- A credit score and past defaults.
Applicant information -age ,income ,education and employment status
Loan amount- the total amount requested. large amount may required more scrutiny.
Loan status - In that we can see the customer history loan status.
property Area- Geographical location of the property a loan applicant is using.
Income-Monthly or annual income of the applicant.
maried- The applicant is married or single.
Dependence-Number od dependents the applicant has.
Loan amount Term- Duration of the loan repayment period.
Education- Graduated and not graduated.
# Problem Statement 
Dream housing Finance company deals in all home loans. they have presence across all urban, semi urban and rural areas. customer first apply for home loan after that company validates the customer eligibility for loan.
loan prediction is a very commmon real life problen tha every retail bank faces in their lending operation if the loan process is automated, it can save a lots of man hours and improve the speed of service to the customer.
# Data collection
THe data i have get the data in kaggle.com free there are 13 column and 614 rows. 
# EDA(exporatory data analysis)
we will use  python to explore the data in order to gain a better understanding of the features and target variable. we will also analyze the data summerize their main characterisics,using various visualization techniques.
Explore the distribution of individual features both numerical and categorical use histogram, box plots, or bar chart to visualize the data.
** 3-types of data **
object- categorical variable like, Loan id,  gender and other
int- Integer values applicant income.
float- decimal like, coapplicantincome , loan ammount term and other.
# Data Pre processing
 data preprocessing is a data mining techniques that involve transform row data into an understandable formnate . real word data is often incomplete, inconsistence and lacking in certain behavior to trends it can resolving such issues.

# Data splitting
split your data into train and test set to evaluate your models performance.
# model Selection
In that we cn choose a common ML algorithms for binary classifications like logistic regression, random forest. support vector machine and xgboost.
In that i can apply various algorithm and the highest accuracy i got by the logistic regrestion (0.7982) RFC (0.7898), XGBOOST(0.7901), DTC(0.71129),KNC(0.6222) and the SVM(0.68741).

# conclusion
After trying the 6 different algorithm ,the best accurency achived by Logistic Regression (0.7982)
