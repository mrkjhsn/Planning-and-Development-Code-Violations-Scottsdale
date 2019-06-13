## Planning-and-Development-Code-Violations-Scottsdale

The City of Scottsdale publishes a [dataset](http://data.scottsdaleaz.gov/dataset/planning-and-development-code-violations)* that includes closed planning and development cases for one rolling year, updated weekly.  One of the characteristics that interests me about this dataset is that it includes the GIS coordinates of where the violations are located.  With both "open" and "close" dates for violations, this dataset creates a good oportunity to perform time series analysis
___

How does the volume of cases opened and closed compare from day to day?
<br/>
<br/>
![](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/visualizations/Cases%20Opened%20%26%20Closed%20by%20Day%20of%20the%20Year.png)
<br/>
<br/>
<br/>
<br/>
There is a high level of variability from day to day.  For a more general trendline, how does the volume of cases opened and closed compare from month to month?
<br/>
<br/>
![](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/visualizations/Cases%20Opened%20%26%20Closed%20by%20Month%20of%20the%20Year.png)
<br/>
<br/>
<br/>
<br/>
Although the volume of violations tracks quite closely, why is there a spike between August and November?  Does any specific violation category contribute most to the spike at this time of year?
<br/>
<br/>
![](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/visualizations/Cases%20Opened%20by%20Month%20of%20the%20Year%20-%20Top%205%20Violation%20Categories.png)
<br/>
<br/>
<br/>
<br/>
How does the trend for cases closed track among the top 5 violation categories?
<br/>
<br/>
![](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/visualizations/Cases%20Closed%20by%20Month%20of%20the%20Year%20-%20Top%205%20Violation%20Categories.png)
<br/>
<br/>
<br/>
<br/>
A large number of "[18-9 LAND](https://library.municode.com/az/scottsdale/codes/code_of_ordinances?nodeId=REVISED_CODEVO1_CH18PUNUPRMA_ARTIIIPRMA_S18-9LA)" violations issued April - June are closed August - October.  Taking a closer look at "18-9 LAND" violations, do any specific violation codes feature most prominently at specific times of the year?
<br/>
<br/>
![](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/visualizations/Top%205%20LAND%20Cases%20Opened%20by%20Month%20of%20the%20Year.png)
<br/>
<br/>
<br/>
<br/>
For the second highest category of violation([18-5 PUBLIC NUISANCE](https://library.municode.com/az/scottsdale/codes/code_of_ordinances?nodeId=REVISED_CODEVO1_CH18PUNUPRMA_ARTIIPUNU_S18-5PUNU)), what are the top 5 violation codes?  How do those track across the year?
<br/>
<br/>
![](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/visualizations/Top%205%20PUBLIC%20NUISANCE%20Cases%20Opened%20by%20Month%20of%20the%20Year.png)
<br/>
<br/>
<br/>
<br/>
The biggest driver of case volume seems to be landscaping(grass too long, dead shrub, ect.) and tracks consistently with periods of rain, and lack of rain throughout the year.  For a full details take a look at my analysis in this [Jupyter Notebook](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/Code_Violations_Annual_Trends.ipynb).
<br/>
<br/>
___
#### To investigate further:
1. How are various code violations geographically distributed throughout the city?
3. Based on different types of violations, what is the difference in time between when a complaint is received and when it is closed?  What does this say about how different sorts of code violations are enforced?
___
*Contains information from the City of Scottsdale Open Database Portal, which is made available here under the [Open Database License](http://www.scottsdaleaz.gov/AssetFactory.aspx?did=69351).
