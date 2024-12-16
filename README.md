# neural-network-challenge-1
I am working at a company that specializes in student loan refinancing. If the company can predict whether a borrower will repay their loan, it can provide a more accurate interest rate for the borrower. My team and I have been asked to create a model to predict student loan repayment.

The business team has given me a CSV file that contains information about previous student loan recipients. With my knowledge of machine learning and neural networks, I will decide to use the features in the provided dataset to create a model that will predict the likelihood that an applicant will repay their student loans. The CSV file contains information about these students, such as their credit ranking.

* I Prepared the data for use on a neural network model.

* I Compiled and evaluated a model using a neural network.

* I Predicted loan repayment success by using the neural network model of my choice.

* Here, I'll discuss creating a recommendation system for student loans.

**Question 1**
Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.

In order to build a recommendation system to recommend student loan options for students in the most accurate and successful way, several types of relevant and appropriate data would be needed. In this exercise, the target data was credit ranking. The classification report for these predictions 0.74, letting us know that it did reasonably well. This information is widely used for loan decisions and is a solid representation of the borrowers' financial history. It is crucial that the aquired data is relevant and appropriate to the filtering system. Demographics are also a primary source of relevant data. Things such as the student's age will show experience handling responsibilities as well as how many years they have had to build responsible habits. Income level is debatable because it can be assumed that they are in need of the loan in order to pay for the education to then increase their income. However, it is still neccessary to know that the student has a form of income in order to make the payments before their career begins. This helps to form the appropriate match for loan type to student type as well, such as repayment options and interest rates. Field of study will also give the loaner a predictable salary after graduation with job market prospects. Credit history, however, is the overall choice for this model.


**Question 2**
Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.

This recommendation system useses credit ranking as the target feature which is content-based filtering. This works with the user's pervious interactions with similar topics to help predict future choices; in this case, the student's credit history. We also could have used data such as payment history, gpa ranking, financial aid score, loan score, or finance workshop score to fit a similar filtering process. If we had used features such as location parameter or time to completion, this would have been context-based filtering. This filtering works with a unique range of information like time of day, location, and user activity rather than just user choices. Collaborative filtering uses other users' preferences and choices to help with predictions. This can be either user-based or item-based, but ideally uses the same methodology. This is useful to personalize a target by leveraging the collective information. So past experiences of how students' loans have been executed allows for future predictions to find the best suited loan for each person. Feature options for this style of filtering could be cohort ranking, alumni success, and study major code. While a great deal of data is needed for this type of filtering it could prove to be quite successful. However, in this exercise we chose credit history in order to use a content-based filtering predictive model.


**Question 3**
Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.

Real-world challenges that ought to be considered while building a recommendation system for student loans are complicated but neccessary as these loans can set a student up for success and their persuit of happiness. Keeping influencial factors such as loan interest rates, financail aid, and economic conditions constantly updated is of the utmost importance. These elements change regualry and play a large roll in this decision making process. Secondly, I think a socialogical aspect that should be of concern is the period of life known as adolescence. This stage of a person's life has increased by at least a decade over the last century. This chapter of life plays a large part in the growth of a student in the loan assessing situation. When looking for a student's responsibility crudentails, there may not be enough data. Students may live at home with their parents support much longer now rather than building their life independence skills that can be measured and utilized in a filtering system such as this.

