### The City of Scottsdale publishes a city code violations [dataset](http://data.scottsdaleaz.gov/dataset/planning-and-development-code-violations) that includes one rolling years worth of data, updated weekly.  I'm interested in exploring annual trends in code violations.  

### How does the volume of cases opened and closed compare from day to day?
<br/>
<br/>

![](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/visualizations/Cases%20Opened%20%26%20Closed%20by%20Day%20of%20the%20Year.png)
<br/>
<br/>
### There is a high level of variability from day to day.  For a more general trendline, how does the volume of cases opened and closed compare from month to month?
<br/>
<br/>

![](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/visualizations/Cases%20Opened%20%26%20Closed%20by%20Month%20of%20the%20Year.png)
<br/>
<br/>
### Although the volume of violations tracks quite closely, why is there a spike between August and November?  Does any specific violation category contribute most to the spike at this time of year?
<br/>
<br/>

![](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/visualizations/Cases%20Opened%20by%20Month%20of%20the%20Year%20-%20Top%205%20Violation%20Categories.png)
<br/>
<br/>
### How does the trend for cases closed track among the top 5 violation categories?
<br/>
<br/>

![](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/visualizations/Cases%20Closed%20by%20Month%20of%20the%20Year%20-%20Top%205%20Violation%20Categories.png)
<br/>
<br/>
### A large number of "[18-9 LAND](https://library.municode.com/az/scottsdale/codes/code_of_ordinances?nodeId=REVISED_CODEVO1_CH18PUNUPRMA_ARTIIIPRMA_S18-9LA)" violations issued April - June are closed August - October.  Taking a closer look at "18-9 LAND" violations, do any specific violation codes feature most prominently at specific times of the year?
<br/>
<br/>

![](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/visualizations/Top%205%20LAND%20Cases%20Opened%20by%20Month%20of%20the%20Year.png)
<br/>
<br/>
### The second highest category of violation is ([18-5 PUBLIC NUISANCE](https://library.municode.com/az/scottsdale/codes/code_of_ordinances?nodeId=REVISED_CODEVO1_CH18PUNUPRMA_ARTIIPUNU_S18-5PUNU)).  Public Nuisance is an extremely broad category - everything from "animal manure" to "noxious exhalations" to "attractive nuisances"  What are the top 5 violation codes?  How do those track across the year?
<br/>
<br/>

![](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/visualizations/Top%205%20PUBLIC%20NUISANCE%20Cases%20Opened%20by%20Month%20of%20the%20Year.png)
#### Above:  18-5(11) are code violations due to "Plant growth or any other condition, sign, structure, vehicle or watercraft that obstructs or interferes with or renders dangerous the use or passage of any public place, stream or water course."  It's unclear to me why the quantities of this violation are so elevated for the months of June and October.  It's interesting that plant growth is covered under this code violation, as well as Section 18-9 above.  It's possible this is more of a catch all code for plant violations that don't fit into 18-9.
<br/>
<br/>

### Overall, the biggest driver of case volume seems to be landscaping(grass too long, dead shrub, ect.) and tracks consistently with periods of rain, and lack of rain throughout the year.  For full details, take a look at my analysis in this [Jupyter Notebook](https://github.com/mrkjhsn/Planning-and-Development-Code-Violations-Scottsdale/blob/master/Code_Violations_Annual_Trends.ipynb).
<br/>
<br/>
