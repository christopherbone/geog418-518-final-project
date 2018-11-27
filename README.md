# geog418-518-final-project

Code and data for final project

All the code available here is for completing the final project for Geog 418. Please keep in mind that the PM2.5 data needs to
be modified in order for it to be used with the code. Currently, the PM2.5 values in this .csv file are stored as factors, and
need to be converted to numeric. You can do this either in worksheet editor like Excel, or you could write some simple code 
using the as.numeric function to convert this column to a numeric data type. Once you have done that, you can then delete the 
NA values using the na.omit function.

The general methods for completing this project are as follows:
1. Clean up the data
2. Perform descriptive statistics on the variables
3. Create plots and maps of the variables
4. Perform a linear regression
5. Determine if the residuals from the regression analysis are spatially clustered
6. If so, perform geographically weighted regression
7. Evalate your sampling structure to determine if the air quality measurements are randomly distributed
