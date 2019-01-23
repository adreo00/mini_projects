# CircleUp
### Background
user_message
You’ll see that it is a csv file with 28,371 rows and 4 columns. Each row in the table represents a ‘content creation event’ -- Here are some additional details about each column:

user_id - The id of the user in the system
content_created - The date of the event (always between Jan 1, 2015 – Dec 31, 2015)
content_count – A summary count of the total number of content a user created for the event
total_engagement – A sum total of all the positive customer engagement associated with the event

user
You’ll see that it is a csv file with 5,317 rows and 2 columns.

user_id - The id of the user in the system
content_created - A internally defined event that can be represented by an binary outcome

user_features
You’ll see that it is a csv file with 5,317 rows and 13 columns.

user_id - The id of the user in the system
var _1 … var_12 - 12 variables that represent features we have been able to derive about a user that can be used to predict the above binary outcome (e.g. content_created)

model_test_file
You’ll see that it is a csv file with 59 rows and 13 columns - It follows the exact format as the user_features dataset.

### Questions
Question 1 - Use the user_message dataset
Write a function that calculates the total number of content a user had created over the last year and report the users who have greater than 500 pieces of content created
Define a metric and a corresponding function that determines which are the fastest growing users in terms of positive customer engagement over the last year. Report the top 10 users based on the metric that defines “fastest growing user”

Question 2 - Use the user, user_features & model_test_file datasets
Write a function that takes as input the user features and outputs the predicted response variable (e.g. content_created) found in the user dataset
Report the predicted response for the users in the model_test_fileIf you use any visualizations/ metrics to validate the model please include them in the reportPlease explain the reasoning behind the technique you used to build the model

## Results
If you would just like to view the results, you can open the [HTML file](https://htmlpreview.github.io/?https://github.com/adreo00/other/blob/master/analysis.html) without installing anything.

### Prerequisites

If you want to interact with my code, this will install the necessary packages to run the .ipynb file.

```
pip install -r requirements.txt
```

### Running Jupyter Lab

For information related to Jupyter Lab please go to https://github.com/jupyterlab/jupyterlab
