# Online Retail Analysis

**Online Retail Analysis** is a tool designed to inform business decisions through data analysis and visualisation. This tool is built using Python, Pandas, Plotly, Seaborn, Matplotlib, and Tableau. This tool reads from a raw CSV file, processes the data and shows visualisation insights in a jupter notebook and a Tableau dashboard.

## Dataset Content
* [Online Retail Dataset](https://www.kaggle.com/datasets/abhishekrp1517/online-retail-transactions-dataset)

The dataset contains transactional data from a UK-based online retail store. It includes information about customers, products, and transactions, with the following key features:

- InvoiceNo: Unique identifier for each transaction
- StockCode: Unique identifier for each product
- Description: Text description of the product
- Quantity: Number of units sold
- InvoiceDate: Date and time of the transaction
- UnitPrice: Price per unit of the product
- CustomerID: Unique identifier for each customer
- Country: Country of the customer

## Business Requirements
As this is an online retail analysis project, the business requirements may include:
1. **Sales Performance Analysis**: Analyse sales trends over time, identify peak sales periods
2. **Enhancing Customer Retention**: Identify repeat customers, analyse customer purchase behavior such as frequency and value of purchases
3. **Product Performance**: Identify top-selling products, analyse product categories, and assess inventory turnover rates
4. **Geographical Insights**: Analyse sales performance by country or region to determine where to focus marketing efforts
5. **Inventory Management**: Use sales data to inform inventory decisions, such as which products to stock more of and which to discontinue


## Hypothesis and how to validate?

* Hypothesis 1 - The most popular products generate higher revenue during a particular season in the year, highlighting the importance of aligning inventory and marketing strategies with seasonal buying behaviour. 

* Hypothesis 2 - The drive for the majority of the revenue comes from the contributions made by the top 10% of customer.

* Hypothesis 3 - Quarter 4 of the year (Oct-Dec) has an increase in sales due to the seasonal holidays

* Hypothesis 4 - customer who purchase more frequently tend to spend more per transaction 

Validation for these hypothses listed above will be demonstrated using various visualiations and commentary within the data visualisations jupyter notebook. This will help the team to understand whether they are true or false. 

## Project Plan
1. Data Collection 
    * Gather the dataset from Kaggle
2. Data Cleaning and Preprocessing
    * Handle missing values, remove duplicates, and correct data types
    * Filter out irrelevant data (e.g., transactions with negative quantities, product descriptions that are not products such as "damages and ?")
    * Create new features (e.g., TotalPrice = Quantity * UnitPrice)
3. Save the cleaned data to a new CSV file
4. Explore Data and visualise
    * Use descriptive statistics to understand the data
    * Create visualisations to identify trends and patterns for key insights of the data in line with hypotheses
5. Dashboard Creation
    * Use a wireframe and Tableau to plan and create an interactive dashboard that includes key metrics and visualisations in line with the hypotheses
6. Presentation
    * Create a presentation with our key insights and conclusions in line with the hypotheses.

## The rationale to map the business requirements to the Data Visualisations

- Enhance customer retention/engagement
- Optimise product offerings (inventory management)
- Strategic sales growth

The business requirements would be met through understanding the data after processing and visualisations. This gave the team an idea on solutions for the business requirements to be met

 It is common in the retail industry to look at sales, seasonality, cusomters and their characteristics in spending and the products being bought.

## Analysis techniques used
- Researching and using the standard key metrics for an online retail industry, this helped reach my objectives and gain a better understanding on the dataset.
- We structured the analysis around what a common retail industry would want to look at and gathered some idea's surrounding the generalised view of the industry. This gave our team a base on structure to go by, sales, products, customers etc.
- Generative AI alongside the teams knowledge and expertise helped with some bits of code where its suggesting lines of code or speeding up code writing with assumptions that we deemed correct to use.
- Online resources such as youtube and google was used for code understanding and helped with code building

## Ethical considerations
* The dataset came from Kaggle and presumably would not have any legal or societal issues. There was no personal data within the dataset which could expose or identify any thing perosnal to a particular individual.

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* With the teams skillset and expertise, the team did not encounter any major issues. We were all on call for support where needed with a solid project plan in place. A lot of the issues people may have come across in the first project have been rectified and newly learnt, therefore referring back to experience in these situations was the solution.
* New skills or tools the team plan to learn is understanding VSCode more, dashboard tool and python. This would aid in more hands on experience to build more understanding and confidence in completing projects.

## Main Data Analysis Libraries
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Tableau


## Credits 

* Kaggle Dataset: [Online Retail Dataset](https://www.kaggle.com/datasets/abhishekrp1517/online-retail-transactions-dataset)
* Generative AI tools: ChatGPT, GitHub Copilot
* YouTube
* Team members


### Contributors:
- Mahabir - Project Manager / Data Architect / Analyst
- Stephen - Project Manager / Data Architect / Analyst
- Adrian - Data Architect / Analyst
- Rana - Data Architect / Analyst
- Tanzila - Data Architect / Analyst

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
