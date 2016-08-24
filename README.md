# CapStone
•	An introduction to the problem (based on your earlier Capstone submissions).

This project seeks to discover relevant variables affecting Omaha metro consumer purchasing trends as it relates to sandwich shops. Customer demand is affected by a multitude of variables that are hard to determine. While I was operating a local sandwich shop it was nearly impossible for me to judge our demand for a particular day. This caused a multitude of issues for the company. As a food vendor we must order weekly due to the perishable nature of the product we produce. I hope to use key indicators to predict the demand on a particular day. Knowing the potential demand will allow for improved ordering which reduces waste and improves efficiencies. 
I plan on using Stock Pricing, Fuel Prices, Sales Data, University of Nebraska – Omaha Crime Data, Temperatures, and Rain Fall. Stock Pricing, the closing stock price of multiple fortune 500 business in the Omaha metro as economic indicators. The variations in stock prices will help to identify fluctuations in the local market as the companies are closely tied to the local economy. Fuel Prices, this is a variable that can have a significant impact on the expendable budgets of consumers. Sales Data, I will be using historical sales data to develop models against. With this data I will be able to discover key influencers as compared to other data points. University of Nebraska – Omaha Crime Data, criminal data can have impacts that are not easily seen I will be utilizing this data as a way of looking for erroneous and unique factors. Temperatures, daily temperatures can impact travel and shopping habits; with the temperature we can see what key points have the largest impact on the consumer’s behavior. Rain Fall, daily rain can impact travel and shopping habits; with the rain data we can see what key points have the largest impact on the consumer’s behavior.

A deeper dive into the data set:
o	What important fields and information does the data set have?

Stocks contains fields containing date, close price, volume, open price, high, and low. The Stocks data sets are five historical stock information on Werner, Union Pacific, First Data, Walmart, and Conagra.  Each data set contains the closing price for each of the companies, it is with this that I plan on using to model against. With increases and decreases in the prices compared to customer sales I plan on showing the impact each of these variables might have as influencers.

Fuel Prices contains date and weekly U.S. all grades all formulations retail gasoline. Fuel prices have far reaching impacts on economics systems as a whole. With a submarine sandwich be considered a convenience item it is likely that a reduction in discretionary funds will impact customer sales. I seek to infer the significance that the fluctuations in the gas price may have on consumer behavior. 

Sales Data contains date, category, item, qty, modifiers applied, gross sales, tax, device name, and event type. I will be using historical sales data build the models as this will be the variable I am looking to influence. The number of transactions will be the important information; this can be found in the number of duplicate dates. Each unique transaction is represented by a new line. The total number of counts for a particular date represents the total consumer transactions for a particular day.

University of Nebraska – Omaha Crime data contains case number,	incident code,	reported, case status, start occurred,	end occurred, building	location, stolen	damaged, and description. I will be looking for unique outliers to find significant influencers that might impact the consumer sales count. I will be using this data to see if a crime in the local area on a particular day will impact the model. 

Temperature contains date, tempature High (°F), tempature Low (°F) precipitation MTD (Inch), percipitation YTD (Inch), snow MTD (Inch), snow YTD (Inch) and rain. The weather is an important variable as you know if it is raining, hot, or any number of weather related activities you may not want to venture out to a food vendor. I will be using this data to see if rain or temperature has an impact on the consumer sales.

Rain Fall is presented as a column in the temperature data set.


o	What are its limitations i.e. what are some questions that you cannot answer with this data set?

My data is extremely quantitative and far from absolute inclusion. I will not be able to account for any qualitative factors or external events. Knowing that there will be outliers intend on removing them from the data. 

o	What kind of cleaning and wrangling did you need to do?

Most data sets will just require data manipulation using dplyr; typically column removal and joining of data sets. I will also need to convert individual dates to counts and combine independent data sets.

•	Any preliminary exploration you’ve performed and your initial findings.

At this point I have been working on data wrangling; I have managed to clean the data sets and have begun merging the data sets. I plan on beginning to run models tonight and through the weekend. 
