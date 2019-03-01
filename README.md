# Interview Questions #

Imagine you have been tasked by the Account Manager to create a basic reporting application that will allow the account manager to view complaints via a online portal.
The company has provided you with a CSV file with all the complaints that the business has recieved and the number of corresponding sales in that period.

## 1. Create an express app with a GET /data/cpmu route

- The route or application should read the data from the JSON file.

## 2. Update the route to additionally calculate "CPMU"

- CPMU = Complaints per million units
- The calculation should happen server-side

For example:

|Month       | CPMU|
|---------- | ----------|
|January 2012|	5.47|
|February 2012|	57.66|
|March 2012|	12.13|
|May 2012|	67.78|
|June 2012|	93.68|

## 3. Update the route to fill-in missing data when not available

- These values should be displayed as "No Value"

For example:

|Month       | CPMU|
|---------- | ----------|
|February 2012|	57.66|
|March 2012|	12.13|
|April 2012|	No Value |
|June 2012|	93.68|
|July 2012|	57.30|

## 4. Develop a basic reporting portal using React library

![Example Reporting Portal](/example-2.png "Example Reporting Portal")

# The Test #
Hopefully, completing the test itself shouldn’t be too difficult, but to help:
- The file `interview.xlsx` has been provided by the project manager as an example of correct calculations.
- We are looking for how you approach the project, the tests you put in place, the structure of your code etc.
- You should approach this as if it were part of much bigger interconnected project.
- The project manager is conscious of the development budget, so your solution should be economical without compromising quality while delivering all the requirements.
