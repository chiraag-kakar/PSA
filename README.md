# The-Android-App-Market-on-Google-Play
This project makes a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. 
It will also look for insights in the data to devise strategies to drive growth and retention.

The data for this project was scraped from the Google Play website. While there are many popular datasets for Apple App Store, there aren't many for Google Play apps, which is partially due to the increased difficulty in scraping the latter as compared to the former. The data files are as follows:

*apps.csv*: contains all the details of the applications on Google Play. There are 13 features that describe a given app.

*user_reviews.csv*: contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity.
