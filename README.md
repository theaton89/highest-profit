# highest-profit
 Read a CSV file containing corporate profits over the years and create JSON format data and look for highest profit values in the data.

# Output
The main.js file parses the data.csv file and provides
1) The number of rows of data
2) The number of rows containing only valid numerical data in the "Profit (in millions)" column
3) The top 20 companies with the highest Profit values.


# Design
I used the csv-parser package to quickly parse the large amount of data in the data.csv file. 
