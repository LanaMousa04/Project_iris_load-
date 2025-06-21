# Project_iris_load-
A web application that uses machine learning to classify iris flower species based on user-provided measurements. Built with scikit-learn
# What I did:
I started by exploring the classic Iris dataset. I applied filtering to remove rows with short sepal lengths, engineered new features like the sepal length-to-width ratio, and categorized the sepal length into levels (Low, Medium, High).
In addition, I implemented **web scraping** scripts to collect extra information about iris flower species from online sources. This data could be used for enriching the dataset or adding insights to the web interface.

# Machine Learning:
I trained a **Logistic Regression** model using `scikit-learn` after scaling the features with `StandardScaler`. I evaluated the model with accuracy metrics to ensure it performs well on unseen data.

### Web Application:
 I saved a sample of the data into JSON format for future use or sharing.
 
### Tools & Technologies:

- Python
- Pandas, NumPy, Scikit-learn
- BeautifulSoup / Requests (for web scraping)
- Django (for the web interface)
- Visual Studio Code 

