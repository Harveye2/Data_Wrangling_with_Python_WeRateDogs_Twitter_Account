# Data_Wrangling_with_Python_WeRateDogs_Twitter_Account
## Introduction
WeRateDogs is a Twitter account that rates people's dogs, along with a comment about the dog, based on the pictures posted to the account. Data from the WeRateDogs Twitter account was gathered from the twitter API and a csv file containing data was also provided. Furthermore, a tweet image predictions file was programmatically downloaded from the Udacity server (using Python's Requests library) which contained the predicted breed of dog (or other object, animal, etc.) present in each tweet's image, according to a neural network. The data was assessed for quality and tidiness issues, cleaned and stored.  Finally, the data was analysed to gain insights into the WeRateDogs twitter account.

## Installation
The following Python libraries were imported for the purpose of this project:
-  pandas
-  matplotlib
-  numpy
-  sqlalchemy
-  requests
-  os
-  json
-  tweepy

## Data
The initial data files gathered for this project, and stored in the 'Gathered_data' folder:
1) 'twitter_archive_enhanced.csv" file (downloaded manually from the Udacity website)
2) 'image_predictions.tsv' file (programmatically downloaded from the Udacity server)
3) 'tweet_json.txt' file (obtained from the Twitter API)

The final data files saved, afer assessing and cleaning the data, and stored in the 'Cleaned_data' folder:
1) 'twitter_archive_master.csv' file 
2) 'image_predcitions_clean.csv' file

The project documents:
1) 'WeRateDogs_Data_wrangle_code.ipynb' (jupyter notebook containg the code for gathering, assessing, cleaning, storing and analysing the data)
2) 'WeRateDogs_Data_wrangle_report.ipynb' (a report that describes the data wrangling process.  Also available as a HTML document).
3) 'WeRateDogs_Data_analysis_report.ipynb' (a report that communicates the insights and displays the visualizations produced from the wrangled data.  Also available as a HTML document).

## Note About Code
In the 'WeRateDogs_Data_wrangle_code.ipynb' juputer notebook, the code used to query the Twitter API has been altered.  The Twitter API keys, secrets, and tokens used to access this data have been removed.  Also, the remaining code used to query the Twitter API, and to download the 'image_predictions' file from Udacity's server, were commented out once the required data was obtained.  This code took a couple of hours to run and therefore, in order prevent delays when running the other code blocks in the jupyter notebook following updates, it was preferred to comment out this code.
