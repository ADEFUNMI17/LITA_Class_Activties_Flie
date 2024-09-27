# LITA_Class_Activties_Flie
Data Analyisis File Upload
Data analysis is the process of inspecting, cleansing, transforming, and modeling data with the goal of discovering useful information, informing conclusions, and supporting decision-making.[1] Data analysis has multiple facets and approaches, encompassing diverse techniques under a variety of names, and is used in different business, science, and social science domains.[2] In today's business world, data analysis plays a role in making decisions more scientific and helping businesses operate more effectively.[3]

Data mining is a particular data analysis technique that focuses on statistical modeling and knowledge discovery for predictive rather than purely descriptive purposes, while business intelligence covers data analysis that relies heavily on aggregation, focusing mainly on business information.[4] In statistical applications, data analysis can be divided into descriptive statistics, exploratory data analysis (EDA), and confirmatory data analysis (CDA).[5] EDA focuses on discovering new features in the data while CDA focuses on confirming or falsifying existing hypotheses.[6][7] Predictive analytics focuses on the application of statistical models for predictive forecasting or classification, while text analytics applies statistical, linguistic, and structural techniques to extract and classify information from textual sources, a species of unstructured data. All of the above are varieties of data analysis.[8]

Data integration is a precursor to data analysis, and data analysis is closely linked to data visualization and data dissemination.[9]

Data analysis process

Data science process flowchart from Doing Data Science, by Schutt & O'Neil (2013)
Analysis refers to dividing a whole into its separate components for individual examination.[10] Data analysis is a process for obtaining raw data, and subsequently converting it into information useful for decision-making by users.[1] Data is collected and analyzed to answer questions, test hypotheses, or disprove theories.[11]

Statistician John Tukey, defined data analysis in 1961, as:

"Procedures for analyzing data, techniques for interpreting the results of such procedures, ways of planning the gathering of data to make its analysis easier, more precise or more accurate, and all the machinery and results of (mathematical) statistics which apply to analyzing data."[12]

There are several phases that can be distinguished, described below. The phases are iterative, in that feedback from later phases may result in additional work in earlier phases.[13] The CRISP framework, used in data mining, has similar steps.

Data requirements
The data is necessary as inputs to the analysis, which is specified based upon the requirements of those directing the analytics (or customers, who will use the finished product of the analysis).[14][15] The general type of entity upon which the data will be collected is referred to as an experimental unit (e.g., a person or population of people). Specific variables regarding a population (e.g., age and income) may be specified and obtained. Data may be numerical or categorical (i.e., a text label for numbers).[13]

Data collection
Data is collected from a variety of sources.[16][17] A list of data sources are available for study & research. The requirements may be communicated by analysts to custodians of the data; such as, Information Technology personnel within an organization.[18] Data collection or data gathering is the process of gathering and measuring information on targeted variables in an established system, which then enables one to answer relevant questions and evaluate outcomes. The data may also be collected from sensors in the environment, including traffic cameras, satellites, recording devices, etc. It may also be obtained through interviews, downloads from online sources, or reading documentation.[13]

Data processing

The phases of the intelligence cycle used to convert raw information into actionable intelligence or knowledge are conceptually similar to the phases in data analysis.
Data, when initially obtained, must be processed or organized for analysis.[19][20] For instance, these may involve placing data into rows and columns in a table format (known as structured data) for further analysis, often through the use of spreadsheet or statistical software.[13]

Data cleaning
Main article: Data cleansing
Once processed and organized, the data may be incomplete, contain duplicates, or contain errors.[21][22] The need for data cleaning will arise from problems in the way that the datum are entered and stored.[21] Data cleaning is the process of preventing and correcting these errors. Common tasks include record matching, identifying inaccuracy of data, overall quality of existing data, deduplication, and column segmentation.[23] Such data problems can also be identified through a variety of analytical techniques. For example; with financial information, the totals for particular variables may be compared against separately published numbers that are believed to be reliable.[24][25] Unusual amounts, above or below predetermined thresholds, may also be reviewed. There are several types of data cleaning, that are dependent upon the type of data in the set; this could be phone numbers, email addresses, employers, or other values.[26][27] Quantitative data methods for outlier detection, can be used to get rid of data that appears to have a higher likelihood of being input incorrectly.[28] Textual data spell checkers can be used to lessen the amount of mistyped words. However, it is harder to tell if the words themselves are correct.[29]

Exploratory data analysis
Once the datasets are cleaned, they can then be analyzed. Analysts may apply a variety of techniques, referred to as exploratory data analysis, to begin understanding the messages contained within the obtained data.[30] The process of data exploration may result in additional data cleaning or additional requests for data; thus, the initialization of the iterative phases mentioned in the lead paragraph of this section.[31] Descriptive statistics, such as, the average or median, can be generated to aid in understanding the data.[32][33] Data visualization is also a technique used, in which the analyst is able to examine the data in a graphical format in order to obtain additional insights, regarding the messages within the data.[13]

Modeling and algorithms
Mathematical formulas or models (also known as algorithms), may be applied to the data in order to identify relationships among the variables; for example, using correlation or causation.[34][35] In general terms, models may be developed to evaluate a specific variable based on other variable(s) contained within the dataset, with some residual error depending on the implemented model's accuracy (e.g., Data = Model + Error).[36][11]

Inferential statistics includes utilizing techniques that measure the relationships between particular variables.[37] For example, regression analysis may be used to model whether a change in advertising (independent variable X), provides an explanation for the variation in sales (dependent variable Y).[38] In mathematical terms, Y (sales) is a function of X (advertising).[39] It may be described as (Y = aX + b + error), where the model is designed such that (a) and (b) minimize the error when the model predicts Y for a given range of values of X.[40] Analysts may also attempt to build models that are descriptive of the data, in an aim to simplify analysis and communicate results.[11]

Data product
A data product is a computer application that takes data inputs and generates outputs, feeding them back into the environment.[41] It may be based on a model or algorithm. For instance, an application that analyzes data about customer purchase history, and uses the results to recommend other purchases the customer might enjoy.[42][13]

Communication

Data visualization is used to help understand the results after data is analyzed.[43]
Main article: Data and information visualization
Once data is analyzed, it may be reported in many formats to the users of the analysis to support their requirements.[44] The users may have feedback, which results in additional analysis. As such, much of the analytical cycle is iterative.[13]

When determining how to communicate the results, the analyst may consider implementing a variety of data visualization techniques to help communicate the message more clearly and efficiently to the audience.[45] Data visualization uses information displays (graphics such as, tables and charts) to help communicate key messages contained in the data.[46] Tables are a valuable tool by enabling the ability of a user to query and focus on specific numbers; while charts (e.g., bar charts or line charts), may help explain the quantitative messages contained in the data.[47]

Quantitative messages
Main article: Data and information visualization

A time series illustrated with a line chart demonstrating trends in U.S. federal spending and revenue over time.

A scatterplot illustrating the correlation between two variables (inflation and unemployment) measured at points in time.
Stephen Few described eight types of quantitative messages that users may attempt to understand or communicate from a set of data and the associated graphs used to help communicate the message.[48] Customers specifying requirements and analysts performing the data analysis may consider these messages during the course of the process.[49]

Time-series: A single variable is captured over a period of time, such as the unemployment rate over a 10-year period. A line chart may be used to demonstrate the trend.[50]
Ranking: Categorical subdivisions are ranked in ascending or descending order, such as a ranking of sales performance (the measure) by salespersons (the category, with each salesperson a categorical subdivision) during a single period.[51] A bar chart may be used to show the comparison across the salespersons.[52]
Part-to-whole: Categorical subdivisions are measured as a ratio to the whole (i.e., a percentage out of 100%). A pie chart or bar chart can show the comparison of ratios, such as the market share represented by competitors in a market.[53]
Deviation: Categorical subdivisions are compared against a reference, such as a comparison of actual vs. budget expenses for several departments of a business for a given time period. A bar chart can show the comparison of the actual versus the reference amount.[54]
Frequency distribution: Shows the number of observations of a particular variable for a given interval, such as the number of years in which the stock market return is between intervals such as 0–10%, 11–20%, etc. A histogram, a type of bar chart, may be used for this analysis.[55]
Correlation: Comparison between observations represented by two variables (X,Y) to determine if they tend to move in the same or opposite directions. For example, plotting unemployment (X) and inflation (Y) for a sample of months. A scatter plot is typically used for this message.[56]
Nominal comparison: Comparing categorical subdivisions in no particular order, such as the sales volume by product code. A bar chart may be used for this comparison.[57]
Geographic or geospatial: Comparison of a variable across a map or layout, such as the unemployment rate by state or the number of persons on the various floors of a building. A cartogram is a typical graphic used.[58][59]
