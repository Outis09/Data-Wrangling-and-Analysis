The aim of this project is to gather, assess and clean data enough to perform statistical analysis and visualizations to derive insights from the data.

I analyzed the tweet archive of Twitter user, [WeRateDogs](https://twitter.com/dog_rates). I gathered the dataset from three different sources. That is, a csv file, a tsv file hosted online and tweet json data on Twitter. The csv file contained the tweet archive of WeRateDogs and it was provided by Udacity therefore i downloaded it manually and read it into a dataframe. The tsv file contained image predictions and it was hosted on Udacity servers. I downloaded it programmatically and read it into a dataframe. The third data used was the json data for each tweet ID. I used a Twitter API to retrieve this data and read it into a dataframe.

After gathering the data, I assessed it both programmtically and visually and listed the quality and tidiness issues I discovered. After assessment, I proceeded to clean the dataframes of the issues and merged the three dataframes into one master dataframe which I used for my analysis and visualizations.

I used the Numpy, Pandas and Matplotlib python libraries in this project.

The Jupyter notebook i used can be found in [we_rate_dogs.ipynb](https://github.com/Outis09/Data-Wrangling-and-Analysis/blob/main/we_rate_dogs.ipynb)

I have written an article on Medium detailing the insights I derived from my analysis.
