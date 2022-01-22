# Gold-Price-prediction-Excel-and-R
A project that predicts gold price based on several market factors.

## R and Excel 

#### Excel
The data has been collected from various sources, for example gold_price column in the data set has been collected from gold.org(https://www.gold.org/goldhub/data/gold-prices).  

The data is then complied and sorted and cleaned using Mircosoft Excel, and then then imported to R. 

#### R
A few summary statistics and correlatrion analysis has been done to check the revelance of the columns of the data collected.  
The using R inbuilt packages a Multiple regression model has been built and finally we arrive at the formula for predicting gold prices with the factors: Y = 3.631e+03 + (-2.124e+00 x sensex) + (-5.103e-01 x nifty) + (5.408e+02 x usdinr)  
    + (-2.011e+03 x interest rate) + (6.458e+00 x gold demand) + (5.261e-01 x s&p inr) + (1.162e+00 x oil price inr) +- 7239
    
    
