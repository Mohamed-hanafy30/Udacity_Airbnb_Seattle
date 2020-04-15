# Udacity_Airbnb_Seattle

# an article on medium about this project in this [link](https://medium.com/@mohamedabdelrazek_14826/seattle-airbnb-things-you-should-know-before-booking-in-seattle-e28fcff4a02c?source=your_stories_page---------------------------)

## Project Motivation

I was interested in exploring the AirBnB dataset for Seattle. I wanted to better understand the pricing trends, review sentiments and pricing prediction. Some of the questions that I have analyzed are:

1. How does the pricing increase or decrease by season?
2. What is the peak season in Seattle?
3. How does the pricing increase or decrease by neighborhood?
4. Which ones are the priciest neighborhoods in Seattle?
5. How does property types within neighborhoods impact price for the most expensive neighborhoods and most common property types?
6. How can we categorize reviews based on sentiments?
7. Can we map positive and negative sentiments from reviews to neighborhoods to understand which neighborhoonds rank higher on the positive sentiment scale and which ones rank higher on the negative sentiment scale?
8. Can we explore some of the worst reviews for additional insights?
9. Can we predict a price for a given listing?
10. What factors of the listing correlate best for predicting the price?

## Libraries and Installation

This project requires **Python 3.x** and the following Python libraries installed:
- [Numpy](https://numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Scikit-learn](http://scikit-learn.org/stable/_)
- [matplotlib](http://matplotlib.org/)
- [Collections](https://docs.python.org/2/library/collections.html)
- [NLTK](https://www.nltk.org/)

## File DEscription

The Jupyter notebook showcases the analysis done in order to explore the dataset, the data prepartion and wrangling as well as the building of prediction models in order to answer the questions above. The notebook contains markdown cells to help with documentation of the steps as well as to communicate findings based on each analysis.

### Dataset

In this project we have **Three** dataset from **Kaggle** which are posted by **AirBnb** in the following [Link](https://www.kaggle.com/airbnb/seattle/data)

- calendar.csv: calendar availability of listings and price
- listings.csv: information about all the available listings
- reviews.csv: listing reviews by the users

## Summary of the Result

The following key findings from the analysis are summarized below:

1. It was found that the peak season in Seattle is during the summer months from June to August, with the absolute peak being in July.
2. The "Southeast Magnolia" neighborhood was the priciest neighborhood in Seattle, followed by Portage Bay. Rainier Beach was the cheapest.
3. Looking further at neighborhoods and property types, I found out that houses in Portage Bay are the most expensive followed by houses in West Queen Anne and Westlake.
4. With the help of SentimentIntensityAnalyzer, I was able to map the reviews to their respective sentiments of positive, negative or neutral. I found out that 97.2% of reviews were mostly positive, with 1% negative reviews and 1.8% of reviews that were neutral.
5. By exploring review sentiments by neighborhoods, I found out that Roxhill, Cedar Park and Pinehurst were the neighborhoods with the most positive reviews, while University District, Holly Park and View Ridge ranked lower.
6. By exploring the worst reviews, I found out that SentimentIntensityAnalyzer associate non-English reviews with negative sentiments.
7. Using LinearRegression, I was able to predict price based on a prepped and cleaned dataset






