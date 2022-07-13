# Miniproject 2

### [Assignment](assignment.md)

## Project/Goals
This project aims to retrieve data from multiple sources and storing that information in a SQLite database. The data is collected from the Yelp and FourSquare APIs and focuses on the points of interest surrounding the Calgary Stampede. 

## Process
For each of the APIs, authorization was established in order to access the data in JSON format. The data was transformed into a dataframe, then broken down to extract the relevant information to build a SQLite database.

## Results
Each API had its own strength in terms of coverage. Yelp is good at gathering business information, while FourSquare is better at picking up parks and event venues. 

## Challenges 
- Requests at certain endpoints for Foursquare API were not easy to establish
- Different businesses gathered between the APIs, making it difficult make comparisons
- The longitude coordinate require a directional sign to get results

## Future Goals
The Calgary Stampede covers a decent amount of land containing establishments that can be spaced far apart from each other. With more time, the project could be improved to estimate the amount of time visitors can expect to go from one place to another via walking or vehicle.