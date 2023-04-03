## Charles Ashton | Data/Research Professional
### Helping others extract maximum value from their data.

__About__
- Professionally experienced in data analysis and research.
- Author on several publications in scientific journals.
- Holder of a Master of Science in Molecular Microbiology with courses in statistics.

### Real-world Work Sample

__Case:__ 

An e-marketing entrepreneur was using a commercial SaaS product to track customer ordering activity and marketing campaign performance.
That software provided basic descriptive analysis of the data, but the e-marketer wanted a customized analysis to unlock additional insights.

__Approach:__ 

I cleaned and explored the data set that was provided to me, and considered how different variables related to one another. To quantify those relationships, I computed Pearson's Correlation Coefficient (R) for different variable pairs. I derived a new variable, Days Active, to enable time-based correlations. I created a dashboard to present the analysis in an approachable, updatable way. The principal questions I sought to address were:

Q1: Does the historic number of orders increase the longer someone is a customer?
Q2: Does historic Customer Lifetime Value increase the longer a customer has been active?
Q3: Does Historic Customer Lifetime Value increase with the Historic Number Of Orders?

__Result:__ 

The correlation values enabled the client to evaluate the performance of his e-marketing strategy across different dimensions. 

**The graphs below represent some of the analyses I performed for this client.**[^1]

<img width="600" alt="Marketing_graphs_quadrants" src="https://user-images.githubusercontent.com/93352455/167263755-1637e8ff-319e-43a5-a479-0cc00dba1b75.png">

| **A:** Boxplot. Shows the spread of the data. | 
| **B-D:** Scatter plots with ordinary least squares trendlines. |

The *R* values (noted above the scatter plots) represent the strength of association between the variable pairs. The maximum possible *R* value is **1**: a perfect positive correlation. 

Dashboard presentation of the analyses: <img width="1234" alt="Dashboard" src="https://user-images.githubusercontent.com/93352455/229388397-4e00e2d0-2815-4665-9431-48ebf4f59297.png">

Visit: [https://order-data-analysis-dashboard.onrender.com/]

__Partial Interpretation:__ 

Historic customer lifetime value is not strongly correlated with number of days active. 

Historic number of orders is not strongly correlated with number of days active.

Full remarks and interpretation are available in the code notebook: [E-mail Marketing Data Analysis Notebook](Demos/E-mail Marketing Data Analysis v1.1.ipynb)

[^1]: The client's data have been altered to maintain confidentiality.

### Other Data Projects

I have data analysis/machine learning notebooks posted on Kaggle that draw on publicly availabe datasets. These notebooks show the full sequence of steps I employ to clean, prepare, and analyze data.

<img width="550" alt="Data Visualization   Price Prediction" src="https://user-images.githubusercontent.com/93352455/168410218-921a59a2-f16b-4df0-af09-3cff8c7d8b1b.png">

<img width="550" alt="Distributions_skew" src="https://user-images.githubusercontent.com/93352455/168410225-6263e39e-8d06-4f1e-8756-b54f0dc9e3f7.png">

Visit: https://www.kaggle.com/charlesea/code

### Interesting Reading

Concise review of standard deviation, a fundamental concept in statistics: [Standard deviations and standard errors](https://pubmed.ncbi.nlm.nih.gov/16223828/)

Brief overview of data transformation and important considerations: [Data transformations](https://www.biostathandbook.com/transformation.html)

Discussion of potential pitfalls of using log transformation in data analysis: [Log-transformation and its implications for data analysis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4120293/)
