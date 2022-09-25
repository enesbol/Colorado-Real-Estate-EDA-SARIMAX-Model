# Colorado-Real-Estate-EDA-SARIMAX-Model


**Project Goal:**
Deciding which city in Colorado to invest in


**Project Description:**
Monthly median house prices data for Colorado's regions and cities were required, financial / macroeconomic and demographic factors and their effects on house prices were investigated. With the inferences made from these data and the Sarımax model, the cities that will bring the highest profit after 1 year were determined.


****Project Steps****

1 - Data Gathering from Zillow and Redfin

2 - Data preparation for data analysis.

3 - Exploratory data analysis.

4 - Extra Financial and Demographic Data Gathering for improving model performance.

5 - Feature Engineering for investigating which factors affect house prices, selecting features.

6 - Building SARIMAX model for predicting 320 citys 2023 house prices.

7 - Model evaluating and comparison with EDA. 

**Datas:**

****1 - Median House Price Datas****

1.1 - Time Series - Seasonality Adjusted Home Values Data from Zillow : https://www.zillow.com/research/data/

1.2 - Monthly Median Sale Prices from redfin : https://www.redfin.com/news/data-center/


****2 - Financial / Macroeconomic Datas****

2.1 - The Consumer Price Index (CPI)
2.2 - Inflation

https://www.minneapolisfed.org/about-us/monetary-policy/inflation-calculator/consumer-price-index-1913-

2.3 - The US Dollar Index (DXY, DX, USDX)
https://finance.yahoo.com/quote/DX-Y.NYB/history/

2.4 - M1 Money Supply
https://fred.stlouisfed.org/series/M1SL

2.5 - Market Yield on U.S. Treasury Securities at 10-Year Constant Maturity
https://fred.stlouisfed.org/series/DGS10

2.6 - Velocity of M2 Money Stock
https://fred.stlouisfed.org/series/M2V#:~:text=The%20velocity%20of%20money%20is,services%20per%20unit%20of%20time


****3 - Demographic Datas****

3-1 Migration
https://gis.dola.colorado.gov/population/data/regional-data-lookup/

3-2 Colorado Annually Total Population
https://fred.stlouisfed.org/series/COPOP

****4 - Dependent Variable Colorado House Prices****

All-Transactions House Price Index for Colorado Thousand Dollars


****5 - Total Housing Units Data****
https://gis.dola.colorado.gov/population/data/regional-data-lookup/ 






<div style={{display:"flex",flexWrap:"wrap",gap:"20px", alignItems:"center", justifyContent:"center"}} >
   
   <h>Adjusting the frequency of missing data in some cities and filling the missing data.</p>
   <img src="https://user-images.githubusercontent.com/76845631/192099868-30b1d8b1-3657-491a-8b4c-a375757b85ca.png" width="80%"  />
  
   
   <h>Some of the regions yearly ROI's until 2022<p>   
   <img src="https://user-images.githubusercontent.com/76845631/192100116-edbabd9a-9942-4ba7-acfd-4c03d6508d43.png" width="80%" />
   
      
   <h>Denver Median House Price Prediction for 2023 with confidence intervals<p>      
   <img src="https://user-images.githubusercontent.com/76845631/192140262-04f3bf0c-7127-4373-8451-41bd00f96a3a.png" width="80%" />
   
      
   <h>Cities with the highest ROI<p>      
   <img src="https://user-images.githubusercontent.com/76845631/192101464-ac2a6d80-6176-439f-8a60-fbe2a41a078f.png" width="80%" />


</div>

