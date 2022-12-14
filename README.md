<div align="center">
  <h1>About project</h1>
</div>

### Aim
* gather, assess and clean data enough to perform statistical analysis and visualizations to derive insights from the data.

### Data

The data used is the tweet archive of [WeRateDogs](https://twitter.com/dog_rates),a Twiiter user that rates dogs with humorous comments. The data used was gathered from multiple sources.

That is:
* a csv file
* a tsv file hosted online 
* tweet json data on Twitter

The csv file contained the tweet archive of WeRateDogs and it was provided by Udacity therefore I downloaded it manually and read it into a dataframe.

The tsv file contained image predictions and it was hosted on Udacity servers. I downloaded it programmatically and read it into a dataframe. 

The third data used was the json data for each tweet ID. I used a Twitter API,Tweepy, to retrieve this data and read it into a dataframe.

### Actions
After gathering the data, I assessed it programmtically and visually and listed the quality and tidiness issues I discovered. After assessment, I proceeded to clean the dataframes of the issues and merged the three dataframes into one master dataframe which I used for my analysis and visualizations.

I used the Numpy, Pandas and Matplotlib python libraries in this project.

The Jupyter notebook I used can be found in [we_rate_dogs.ipynb](https://github.com/Outis09/Data-Wrangling-and-Analysis/blob/main/we_rate_dogs.ipynb)

**NB:** The table of contents in the file does not work in the notebook on GitHub but works in the [html](https://htmlpreview.github.io/?https://github.com/Outis09/Data-Wrangling-and-Analysis/blob/main/we_rate_dogs.html) file.

I have shared my insights in an article on [Medium](https://medium.com/@ayersamuel07/data-wrangling-and-analysis-insights-from-weratedogs-twitter-archive-28bc9d3862c9).

I also summarised the insights in the Power BI report below.


![dash](https://user-images.githubusercontent.com/104911707/190913728-fc9c31b9-f9f1-4cda-8c9d-00033658e3f4.png)
