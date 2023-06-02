# vianova-case-study

# Population Analysis

This project aims to analyze the population data of cities around the world and identify countries that do not have a metropolis (city with a population greater than 10,000,000).

## Dataset

The dataset used in this project is sourced from the "geonames-all-cities-with-a-population-1000.csv" file. It contains information about the population of cities, including the city name, country, and population.

## Requirements

To run the code, you need to have the following installed:

- Python (version X.X)
- Pandas library
- MySQL Connector library

## Code Explanation

1. The dataset is loaded into a Pandas DataFrame from the CSV file.
2. The column names are modified to match the database table schema.
3. The data is stored in a MySQL database named "cities_populations" with a table named "metropolis".
4. A SQL query is executed to retrieve the countries that do not have a metropolis.
5. The result is saved as a tab-separated value (TSV) file named "result.tsv" ordered by country name.

## Usage

To run the code:

1. Install the required dependencies listed in the "Requirements" section.
2. Modify the database connection details in the code if necessary (host, user, password).
3. Run the Python script.
4. The result will be saved in the "result.tsv" file.

## Contributing

If you have any suggestions or improvements, feel free to open an issue or submit a pull request.
