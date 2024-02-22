# Explring_wealth_accumulation_of_billionaires

Data Analysis 
	The analysis of the data is conducted with consideration of the research questions, prioritizing the response to the initial research question.
1. What are the top 10 countries with the highest number of billionaires?
The data is separated by country of origin, and from there, the total number of billionaires in each country was calculated. The top 10 countries were then determined by sorting the findings from highest to lowest.
Figure-29: Code of Top 10 Countries.
 

Figure-30: Bar Plot of Top 10 Countries with Highest number of Billionaires.

Above bar chart presents a comprehensive summary of the top 10 nations that possess the greatest quantity of billionaires, thereby offering insight into the global distribution of billionaires. According to the chart, the United States holds a significant lead in the number of billionaires with a remarkable 903 individuals, trailed by China with 153 billionaires and Germany with 145 billionaires. Russia's inclusion in the list of over 100 billionaires is a significant observation, highlighting its notable standing within the worldwide community of billionaires. Nonetheless, the chart indicates a notable decline in the quantity of billionaires subsequent to the leading four nations, given that the remaining six nations featured on the list possess fewer than 100 billionaires individually. The chart functions as an informative instrument for enterprises and financiers who aim to comprehend worldwide wealth allocation and formulate judicious resolutions grounded on these discernments.


Figure-31: StopWords of Top 10 Countries with Highest number of Billionaires.




2. What are the most successful sectors/Industries?
We achieved this by grouping the data by industry and computing the total net worth of each industry, then sorting the results in descending order and selecting the top 10 industries.
 
Figure-32: Most Successful Industries.
Figure-33: Most Successful Industries by Net Worth.
These findings shed light on the complexity of measuring the success of industries, as factors such as net worth and the number of billionaires play distinct roles in determining an industry's performance. For investors and businesses alike, these insights are valuable in informing investment decisions and guiding business strategies in industries that have the potential for high returns. By taking a holistic approach and considering both the number of billionaires and their net worth, stakeholders can better navigate the competitive landscape and make informed decisions that ultimately drive success.

 
Figure-34: Bar Plot of Top 10 Industries with Highest number of Billionaires.
 








3. What are the main industries with the highest number of women billionaires?

 
Figure-35: Horizontal Bar Plot of Top 10 Industries with Highest number of Women Billionaires.

The visualization of the top 10 industries with the highest number of women billionaires, presented in a bar chart, indicates that the retail industry is the most prosperous industry for female billionaires, with 17 billionaires. The media and construction industries are the next most successful industries with 13 and 12 female billionaires, respectively. The lack of female billionaires in the pharmaceutical, medical supply, and electronics sectors has raised questions about potential entry barriers and gender inequities. The utilisation of this visualisation has the potential to aid investors and promote diversity and equality within the industry.









4. What age range represents the highest and lowest number of billionaires?



Figure-36: Created new Variable ‘age_group’.


















Figure-37: Counting Billionaires in each age_group.






 

Figure-38: Distribution of Billionaires by Age Group.


The bar chart representing the distribution of billionaires across age ranges reveals that the age range with the highest number of billionaires is 50-60, with a count of 918 billionaires. The age group ranging from 60 to 70 years old displays a significant cluster of individuals who possess a net worth surpassing one billion dollars. Specifically, there are a total of 590 billionaires within this demographic cohort. On the other hand, the demographic group ranging from 20 to 30 years old displays a comparatively low number of billionaires, with only 13 individuals. Compared to other age groups, the demographic consisting of individuals aged 90 to 100 years old displays a relatively lower occurrence of billionaires. The age ranges of 70-80, 40-50, and 80-90 also show a relatively high number of billionaires with counts of 413, 351, and 198, respectively. These findings can guide investment decisions and business strategies by highlighting the age ranges that represent the highest potential for wealth accumulation.
 





5. What additional factors might influence wealth, such as inheritance or self-made wealth?
The dataset "Billionaires.csv" provides valuable insights into the factors that can influence wealth accumulation. While the dataset includes information on the net worth, age, gender, and industry of billionaires, many additional factors can impact an individual's ability to accumulate wealth.
Education, geographic location, economic conditions, social and professional networks, inheritance laws, access to capital, entrepreneurial spirit, innovation, tax policies, and cultural attitudes toward wealth are among the many factors that can play a role in wealth accumulation. It is important to consider these factors in addition to the factors included in the dataset when analyzing wealth patterns among billionaires.
Inheritance is a particularly significant factor in wealth accumulation, and many billionaires inherit their wealth from previous generations. To further explore the impact of inheritance on billionaires' wealth, we can create a new column in the DataFrame called "Inherited" and define a billionaire as inherited if their source of wealth is "Inherited" or "Inherited, Growing". This approach can provide valuable insights into the role of inheritance in wealth accumulation among billionaires.


Figure-39: Created new variable ‘Inherited’.


 
Figure-40: Percentage of Inherited and Non – Inherited.

From the output, we can see that billionaire who inherited their wealth from their father or grandfather have an average net worth of 3.75 billion, while billionaires who did not inherit their wealth have an average net worth of 3.42 billion. This suggests that inheritance, specifically from fathers or grandfathers, plays a significant role in wealth accumulation among billionaires.
It's important to note that the presence of "father" or "grandfather" values in the dataset may not necessarily mean that the billionaire inherited their wealth. There could be other factors at play, such as the billionaire inheriting a business or company that their father or grandfather started. Therefore, it's important to conduct further research and analysis to confirm the impact of inheritance on wealth accumulation among billionaires.


Figure-41: Correlation between Inheritance vs Net Worth.




Age is another factor that can influence wealth accumulation. Here are a few ways in which age might impact wealth:

The age of an individual can have a significant impact on their wealth accumulation, with younger individuals having more time to take risks and pursue higher returns. Experience and retirement planning can also play a role in wealth accumulation, with older individuals potentially having more industry experience and shifting their focus toward wealth preservation. Inheritance and health can also be important factors, with older individuals more likely to receive an inheritance but also potentially facing greater healthcare costs and financial challenges in old age.



Figure-42: Histogram of Billionaire is different age range.
