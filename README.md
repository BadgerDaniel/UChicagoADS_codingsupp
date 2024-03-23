This project explores the correlation between Bank of America (BAC) stock data, including closing prices and trading volume, with the volume of Tweets from BAC's official social media handles throughout 2022. Utilizing Python's powerful data science libraries, this analysis seeks to uncover potential impacts of social media on stock performance.


Methodology
Data Collection: Use yFinance to pull BAC stock data; obtain Tweet volume count from an existing dataset.
Data Preparation & Merging: Perform necessary transformations for data compatibility, merge datasets on date, handling non-trading days by retaining NaN values.
Exploratory Data Analysis (EDA): Conduct visual analysis using Matplotlib and Seaborn to investigate potential correlations.
Lagged Correlation Analysis: Explore if a delayed effect exists between Tweet volume and stock indicators.
Key Findings
Initial analysis does not show a direct correlation between Tweet volume and stock metrics.
Further examination for lagged effects also reveals no significant correlation.
The null hypothesis stands: Social media volume for BAC does not have a discernible effect on its stock performance based on the analyzed data.
Tools & Libraries
Python: Primary programming language.
yFinance: For retrieving stock data.
Pandas: For data manipulation and merging.
Matplotlib & Seaborn: For data visualization.
Conclusion
This analysis provides insights into the complex dynamics between social media activity and stock market performance, demonstrating the need for more in-depth studies in this area.
