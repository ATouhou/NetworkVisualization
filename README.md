# Network

A network visualization.

## Local server
Running the code:
1. Before running the server install nodejs: https://nodejs.org/en/download/ 

2. Run the terminal and navigate to project folder.

3. Run the following command:
    node server.js

4. Then, go to the browser and go to the url: http://localhost:9000 


## Files
### Preprocessing
* **data.sql** generates csv files
* **quote.R** extract quote connections from post.csv
* **transform.py** Transforms the csv files into json files for the dual view
* **/sql_preprocessing** SQL code to extract the csv files in /csv


### Data
* **post.csv** post information
* **quote.csv** quote connection
* **user.csv** user information including user reputation level and total posts

		
