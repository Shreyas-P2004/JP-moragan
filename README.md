# Natural Gas Storage Contract 

# Objective
As a quantitative researcher visualize the data to find patterns and consider what factors might cause the price of natural gas to vary. This can include looking at months of the year for seasonal trends that affect the prices, but market holidays, weekends, and bank holidays need not be accounted for. Each point in the data set corresponds to the purchase price of natural gas at the end of a month, from 31st October 2020 to 30th September 2024.
Analyze the data to estimate the purchase price of gas at any date in the past and extrapolate it for one year into the future. 
Your code should take a date as input and return a price estimate.

# Dataset Used
 <a href = "https://github.com/Shreyas-P2004/JP-moragan/blob/main/Nat_Gas.csv">Dataset</a>

# Questions(KPI)
- Each point in the data set corresponds to the purchase price of natural gas at the end of a month, from 31st October 2020 to 30th September 2024.
- Analyze the data to estimate the purchase price of gas at any date in the past and extrapolate it for one year into the future.
- Your code should take a date as input and return a price estimate.
- Create a prototype pricing model that can go through further validation and testing before being put into production.
- Write a function that takes these inputs and gives back the value of the contract.
- Consider all the cash flows involved in the product.
- The input parameters that should be taken into account for pricing are:

1) Injection dates. 
2) Withdrawal dates.
3) The prices at which the commodity can be purchased/sold on those dates.
4) The rate at which the gas can be injected/withdrawn.
5) The maximum volume that can be stored.
6) Storage costs.

# Codes
 <a href = "https://github.com/Shreyas-P2004/JP-moragan/blob/main/JP_Morgan_task1.ipynb">Code1</a>
 <a href = "https://github.com/Shreyas-P2004/JP-moragan/blob/main/JP_Morgan_task2.ipynb">Code2</a>

# Process
- Imported the pandas, numpy, matplotlib, datetime , sklearn and linear regression libraries.
- Mounted the google drive and read the dataset.
- Plotted the graph for the dates vs the varying prices using matplotlib.
- Selected only the january prices and months.
- Used linear regression to the fit the model.
- Extraploated for the next year.
- Created an array for the next year price.
- Started from the last day of the year and append the dates in the array for current month and year.
- Moved to the first day of the previous month.
- Then moved back one day to get the last day of the current month using timedelta funtion.
- Reversed the array in the ascending order.
- Read the last dates for each month for the year 2025.
- Created a new dataframe for the 2025 dates and prices.
- Did the final analysis of the gas price and forecasted it.
- Predicted the graph using the historical data vs improved gas price model using the sin function.
- Calculated the various parameters in gas storage contracts such as injection rates, withdrawal dates , injection rate , injection withdrawal costs , maximum storage volume and storage cost per month.


 


