# GooglePlayStoreApp
While many public datasets (on Kaggle and the like) provide Apple App Store data, there are not many counterpart datasets available for Google Play Store apps anywhere on the web. On digging deeper, I found out that iTunes App Store page deploys a nicely indexed appendix-like structure to allow for simple and easy web scraping. On the other hand, Google Play Store uses sophisticated modern-day techniques (like dynamic page load) using JQuery making scraping more challenging.

The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market!

# Project objectives
Our datasets include information about applications on Google Play store. According to this datasets, we expect to dig deeper into android market to analyze the factors influence Rate of apps, trends in the app market, determinants of app downloads. Furthermore, analysis on android market may also help drive app-making business to success.

# Description of dataset
We get the datasets from Kaggle. There are two datasets:

The first one is about some information of different apps and contains 13 variables:
Category(Category the app belongs to).
Rating(Overall user rating of the app).

-Reviews(Number of user reviews for the app);

-Size(Size of the app);

-Installs(Number of user downloads/installs for the app);

-Type(Paid or Free);

-Price(Price of the app);

-Content Rating(Age group the app is targeted at - Children / Mature 21+ / Adult);

-Genres(An app can belong to multiple genres (apart from its main category));

-Last Updated(Date when the app was last updated on Play Store);

-Current Ver(Current version of the app available on Play Store);

-Android Ver(Min required Android version.

The second one is the text for reviews and contains 5 variables:

-App(Name of app);

-Translated_Review(User review (Preprocessed and translated to English));

-Sentiment(Positive/Negative/Neutral(Preprocessed));Sentiment_Polarity(Sentiment polarity score);

-Sentiment_Subjectivity(Sentiment subjectivity score).
