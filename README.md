# DataVirtualization_MiniProject_StockAnalysis_Python
Project Overview:

This stock analysis project focused on exploratory data analysis of stock prices. Explore bank stocks and see how they progressed throughout the financial crisis all the way to early 2016.

About the Dataset:

The dataset concludes the stocks infomarion from
  1. Bank of America
  2. CitiGroup
  3. Goldman Sachs
  4. JPMorgan Chase
  5. Morgan Stanley
  6. Wells Fargo

The time period was:

from 2006-01-03 to 2015-12-31.

The main process of the project:
  1. Data preperation.
  2. EDA
  3. Data visualization.

The main observations:
  1. City Group seems crashed at a specific time.
  2. 4 of the banks share the same day for the worst drop.
  3. During the period which we are exloring, the City Group's price is the unstablest. It was the riskest stock of all.

The main libraries which was used in this project:
  1. pandas
  2. numpy
  3. matplotlib
  4. seaborn
  5. plotly

The main technique whcih used in this project:  
  1. Multi-index dataframe processing with pandas.
  2. Dynamic plot.
 
The main data viz of the project:

  1. line plot showing Close price for each bank for the entire index of time.
<img width="545" alt="image" src="https://user-images.githubusercontent.com/93168873/214442352-1e69f51a-862a-4722-a67f-735e12387109.png">

  2. Plot the rolling 30 day average against the Close Price for Bank Of America's stock for the year 2008.
<img width="289" alt="image" src="https://user-images.githubusercontent.com/93168873/214442556-6ebafab6-4b38-4f93-8180-2524982c354f.png">

  3. Seaborn's clustermap to cluster the correlations together.
  <img width="380" alt="image" src="https://user-images.githubusercontent.com/93168873/214442632-72c3baa1-5762-40fd-a80b-6ef55f96ff59.png">
  
  4. Candle plot of Bank of America's stock from Jan 1st 2015 to Jan 1st 2016.
  <img width="619" alt="image" src="https://user-images.githubusercontent.com/93168873/214442752-6eb49512-f9e6-45bd-ba1f-c5fda21fd3bf.png">

  5. Moving Averages plot of Morgan Stanley for the year 2015.
  <img width="641" alt="image" src="https://user-images.githubusercontent.com/93168873/214442881-7cc071fd-2eed-4ec8-bff2-775119c0bb1a.png">
  
  6. Bollinger Band Plot for Bank of America for the year 2015.
  <img width="620" alt="image" src="https://user-images.githubusercontent.com/93168873/214442960-ff9d0359-72d4-4f62-8bde-3c34d0188916.png">
