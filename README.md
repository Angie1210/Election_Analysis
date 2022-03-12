# Election_Analysis

## Overview of the election audit
In this project we are going to audit the Congressional Election for the Colorado Board of Elections. The purpose of the project is to get the voter turnout for each county,the percentage of votes turnouts each county received out of the total votes and determine which county has more voters participations. To accomplish the task we will connect a CSV file to Visual Studio Code in order to get access to the data and be able to write and execute scripts aware of syntax errors and indentations. We will use Python, a CSV Database "election.results.csv", Visual Studio Code. 

## Election Audit Results
The analysis of the election shos that:
* The congressional election has 369,711 votes cast.
* Each county has the following turnouts: 

![Screen Shot 2022-03-11 at 7 49 38 AM](https://user-images.githubusercontent.com/43548929/157901110-f403d63d-36c2-4630-bde6-4c53246d1118.png)

* As we can see the County with the largest amount of votes was *DENVER*.
* The votes were cast as follows.

![Screen Shot 2022-03-11 at 8 14 36 AM](https://user-images.githubusercontent.com/43548929/157905533-e1735973-4d1a-486d-aef4-f0a38a361176.png)

* The Winner was:

![Screen Shot 2022-03-11 at 8 17 02 AM](https://user-images.githubusercontent.com/43548929/157905915-4d6798b4-aa50-470f-92ef-0c5aa4234136.png)


## Election Audit Summary
This script can be implemented in other election analysis, for example you would only need to change the Database file, by changing the ***file_to_load*** variable, you will have to use the computer's directory path of the CSV database that you want to analyze.  Another modification that you would need to make is in the variables of the ***candidate_name*** and ***county_name***, in order to assign the correct columns of our database.  Also, the PRINT commands, so it displays on your output the Strings that you want. The rest of the code, you can use it as it is, because we are reading the database, row by row extracting the information we need to create our dictionaries.

