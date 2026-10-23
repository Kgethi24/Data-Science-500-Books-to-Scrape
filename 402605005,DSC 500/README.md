Name: Maide Letswalo
Student Number: 402605005
Qualification: BSC IN IT
YEAR:1
Semester:2


ABOUT THIS PROJECT
for this assignment, i built an end-to-end data science pipeline using python. The goal was to scrape book data from
the "Book to Scrape" website, clean it up, visualize the tends and built a linear Regression model to see if we can predict 
book prices based on their features (like rating and stock).

WHAT IS IN THIS ZIP FILE?
-DataScience500_project.ipynb - my Jupyter Notebook with all the code (scraping, cleaning, charts and the machine learning model).
-book_clean.csv - the final, cleaned dataset with 1000 book that the model used.
-book_raw.csv - the messy raw data i got straight from the website before cleaning
-README.md- this file explaining the project

TOOLS I USED
To run this notebook, i used python and the following libraries:
-requests and beautifulsoup (for web scraping)
-pandas and numpy (for data cleaning and manipulation)
-matplotlib and seaborn (for the data visualizations)
-scikit-learn (for building the linear regression model)

HOW TO RUN THE CODE
1)open the .ipynd file in pyCharm or Jupyter Notebook
2)Make sure you have the required libraries installed
3)Run the cells from top to bottom (Note: the web scarping takes about 15-20 minutes to run because it politely pauses between requests
to avoid crashing the website).

MY RESULTS AND FINDINGS
-I successfully scraped 1000 books
The Linear Regression Line model gave me a MEAN ABSOLUTE ERROR(MAE) of £12.71 and an R^2 score of -0.0118
Conclusion: the negative R^2 score shows that the model struggles to predict the prices accurately.As stated on the books to scrape 
website, the prices and ratings are randomly assigned, so there is no real mathematical pattern for the model to learn. However, building 
the pipeline was a great learning experience!

GIT URL:
[InternetShortcut]
URL=https://github.com/Kgethi24/Data-Science-500-Books-to-Scrape#data-science-500-books-to-scrape
