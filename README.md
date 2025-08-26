# Simple-backtesting-trade-strategies
This is a side project to back test simple trade strategies (such as dollar cost averaging vs selective buying). The aim is to start simple and build up complexity as I learn more

## 1st Strategy: Dollar cost average (weekly) vs buying @ 10% Dip. 
We are trying to see if dollar cost average strategy of buying every week is better than trying to time the market.  
We are going to compare dollar cost averaging strategy of saving our money until a 10%, 5%, 2% dip in market price from the previous peak. 

### <u>Required libraries</u>
* yfinance
* pandas
* matplotlib
* datetime

</br>

# Issues
| Issue/Bug | Fixed Date |
| --- | --- |
| Dividends are not factored in. Current model does not count dividends as cash inflow, won't be reinvested. | TBD |

## Next Steps
* Fix Dividend
* Change structure so that it's scalable, incorporate multiple dip threshold in dip buying strategy
* create a slider for the variables to create charts and graphs. 

