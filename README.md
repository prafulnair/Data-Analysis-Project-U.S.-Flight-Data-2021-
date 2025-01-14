# Data Analysis and Cleaning Project – U.S. Flight Data (2021)

This project showcases data analysis and cleaning techniques applied to U.S. flight data for the year 2021. It focuses on extracting actionable insights and handling data inconsistencies using **Python** and **pandas**.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Sample Insights](#sample-insights)
- [Acknowledgements](#acknowledgements)

## Project Overview
The project aims to analyze flight performance, cancellations, and delays in the U.S. using a dataset of flight records. The tasks include:
- Identifying canceled flights within specific date ranges.
- Analyzing diverted flights over a specified period.
- Calculating the average airtime for flights between specific airports.
- Detecting and handling missing data in critical columns like departure time.

## Features
- **Canceled Flights Analysis**: Determine airlines with the most cancellations in September 2021.
- **Diverted Flights Analysis**: Count diverted flights during specific date ranges in November 2021.
- **Airtime Analysis**: Calculate the average airtime for flights between Nashville (BNA) and Chicago (ORD).
- **Missing Data Handling**: Identify and process rows with null values in the departure time column.

## Technologies Used
- **Python**: Main programming language.
- **pandas**: For data manipulation and analysis.
- **Google Colab**: Used for collaborative and interactive Python development.
- **CSV Files**: Input dataset in CSV format.

## How to Run
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/flight-data-analysis.git
    ```
2. Open the project in your preferred Python environment (e.g., Jupyter Notebook or Google Colab).
3. Install required libraries:
    ```bash
    pip install pandas
    ```
4. Replace the `Combined_Flights_2021.csv` file path with the appropriate path to your local dataset.
5. Run the `.ipynb` files to view analysis results.

## Sample Insights
- **Canceled Flights**: The airline with the most cancellations in September 2021.
- **Diverted Flights**: Total number of flights diverted between November 20 and November 30, 2021.
- **Average Airtime**: Flights between BNA and ORD had an average airtime of `X` minutes.
- **Missing Data**: Identified rows with missing departure time for further cleaning.

## Acknowledgements
- Dataset: [U.S. Department of Transportation - Bureau of Transportation Statistics](https://www.transtats.bts.gov/).
- Tools: Google Colab, Python, and pandas library.

Feel free to contribute or share your feedback!