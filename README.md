# Basket-Analysis-With-Sagemaker

We intend to design a recommender system to enhance the user experience by suggesting
the next likely product to purchase during the order process in two ways: Content-based and
Collaborative-based. In a Content-based approach, the system recommends the products based
on the user’s data such as their shopping history. Whereas the Collaborative-based approach
considers all users' information to make a suggestion. The algorithm in Collaborative-based
approach tries to find users with common interests and suggests items which a user might get
attracted to, using the users with similar persona. In this project we will be limited towards
building a system which recommends the items out of 49k unique products that we already have
in our dataset and try to find the similarity in the purchase pattern within. Here, we are not
focusing on new product recommendations which are not in our unique products list inside our
dataset.


We will be using AWS as a platform where we will be using Amazon S3
to store the data and Amazon SageMaker to build the automated system.


We are using Amazon Athena as our tool to explore and query the data where we created
the dataframe in Athena and used the sql queries to create and format the table as per
requirement. Amazon Athena was accessed through SageMaker notebook.
