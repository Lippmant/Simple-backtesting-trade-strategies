# Simple-backtesting-trade-strategies
This is a side project to back test simple trade strategies (such as dollar cost averaging vs selective buying). The aim is to start simple and build up complexity as I learn more

## 1st Strategy: Dollar cost average (weekly) vs buying @ 10% Dip. 
We are trying to see if dollar cost average strategy of buying every week is better than trying to time the market.  
We are going to compare dollar cost averaging strategy of saving our money until a 10%, 5%, 2% dip in market price from the previous peak over a fixed period(5 years) 

### <u>Required libraries</u>
* yfinance
* pandas
* matplotlib
* datetime

</br>

# Issues
<table style=   "white-space: pre-line;
                border: 1px solid black;
                ">
    <thead>
        <tr>
            <th>Issue / Bug </th>
            <th>Fixed Date </th>
        </tr>
    </thead>
    <tbody>
        <tr> 
            <td>
            <ul><li>Dividends are not factored in. Current model does not count dividends as cash inflow, model does not reflect dividend reinvestment.
            <b>Fix</b>: The latest version of yfinance pulls adjusted prices (adjusted for dividends, stock split and other coproate actions). Thus, the analysis already factored in dividend reinvestment.</li></ul>
            </td>
            <td>
            2025-09-27
            </td>
        </tr>
    </tbody>
</table>

## Next Steps

* Change structure so that it's scalable, incorporate multiple dip threshold in dip buying strategy
* create a slider for the variables to create charts and graphs. 
* Test the strategy for a period that involves a recession (the last 5 years has been stock boom, and may not be a good sample).


