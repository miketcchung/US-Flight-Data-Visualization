By Mike Chung

This is the final project of Udacity's Data Analyst Nanodegree. In this project, I visualize data and communicate my data findings for US flights from 2006 to 2008.

The United States Department of Transportation's Bureau of Transportation Statistics tracks the performance of domestic flights operated by large air carriers. I downloaded US flight data from 2006-2008 from ASA's <a href='http://stat-computing.org/dataexpo/2009/the-data.html'>Statistic Computing and Graphics website</a>. The variable descriptions can be found described on their website.

My investigation had the following questions:
<ul>
    <li>What months have more delays and cancellations?</li>
    <li>What are the more common reasons for delays and cancellations?</li>
    <li>How does the delay reason and time correlate with the time in the air?</li>
</ul>

In our exploratory data analysis, I found that carriers were the most common reason for cancellations and NAS was the most common reason for delays. Of the flights that had delays, weather and late aircrafts resulted in the longest average delay times. I further discovered that the delay times and air times were left-skewed from the histograms. Interestingly, plotting the correlation between air time and delay time caused me to look closer at the distribution of the air times, and I found out that there was another small mode in the distribution. I found no significant or obvious correlation between air time and delay time for any of the delay reasons. Lastly, I used a line plot to gain insights on the average delay times across each month for each delay reason. There were individual trends for each of the delay reasons with their own maximums and minimums.

From my exploratory data analysis, I selected the data visualizations that presented a story to our audience. I envision presenting these findings to travelers or travel agencies, so I based my slides on answering the following questions:
<ul>
    <li>What months were less likely to be cancelled or delayed?</li>
    <li>What was the effect of the reasons of cancellation and delay across the months?</li>
</ul>
The correlation between air time and delay time, although interesting, was not included in the exploratory data analysis because I decided it did not present any value to our target audience.

In general, I referred often to the <a href='https://docs.python.org/3/'>python documentation</a>, <a href='https://pandas.pydata.org/pandas-docs/version/0.22/'>pandas documentation</a>, <a href='https://matplotlib.org/contents.html'>matplotlib documentation</a>, <a href='https://seaborn.pydata.org/'>seaborn documentation</a> and <a href='https://stackoverflow.com/'>Stack Overflow</a>.
