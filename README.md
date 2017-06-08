# Stockmarket-NLTP
Trying to see rise or fall of market based on the headlines on that day

The dataset has been taken from Kaggle by Aaron


Description:

There are two channels of data provided in this dataset:

News data: crawled historical news headlines from Reddit WorldNews Channel (/r/worldnews). They are ranked by reddit users' votes, and only the top 25 headlines are considered for a single date. (Range: 2008-06-08 to 2016-07-01)
Stock data: Dow Jones Industrial Average (DJIA) is used to "prove the concept". (Range: 2008-08-08 to 2016-07-01)
I provided three data files in .csv format:

RedditNews.csv: two columns The first column is the "date", and second column is the "news headlines". All news are ranked from top to bottom based on how hot they are. Hence, there are 25 lines for each date.
DJIA_table.csv: Downloaded directly from Yahoo Finance: check out the web page for more info.
Combined_News_DJIA.csv: To make things easier for my students, provide this combined dataset with 27 columns. The first column is "Date", the second is "Label", and the following ones are news headlines ranging from "Top1" to "Top25".
"1" when DJIA Adj Close value rised or stayed as the same;

"0" when DJIA Adj Close value decreased.


