# Insights-from-City-Supply-and-Demand-Data

This data project was used as a take-home assignment in the recruitment process for data science positions at Uber.

### Download Datasets

You can download the datasets used in this project from the following source:
- [Dataset](path_to_dataset)

### Project Overview

The objective of this project is to analyze city supply and demand data and derive meaningful insights. The dataset contains information on the number of eyeballs, zeroes, completed trips, requests, and unique drivers recorded at different times over a two-week period.

### Requirements

- Python 3.7+
- Pandas
- Numpy
- Matplotlib
- Seaborn

### Installation

1. Clone the repository:
    git clone https://github.com/yourusername/sncrsenyurt/Insights-from-City-Supply-and-Demand-Data

2. Navigate to the project directory:
    cd your-repo-name

3. Install the required dependencies:
    pip install -r requirements.txt

### Dataset Description

The dataset contains the following columns:
- `Date`: The date of the record.
- `Time (Local)`: The local time of the record.
- `Eyeballs`: The number of eyeballs.
- `Zeroes`: The number of zeroes.
- `Completed Trips`: The number of completed trips.
- `Requests`: The number of requests.
- `Unique Drivers`: The number of unique drivers.

### Analysis and Insights

The project involves answering the following questions and generating insights:

1. **Which date had the most completed trips during the two-week period?**
    - Aggregated the data by date and identified the date with the highest number of completed trips.
    - Plotted a bar chart to visualize the completed trips by date.

2. **What was the highest number of completed trips within a 24-hour period?**
    - Used a rolling window of 24 hours to calculate the total number of completed trips.
    - Identified the 24-hour period with the highest number of completed trips.
    - Plotted a line chart to visualize the completed trips within a 24-hour rolling window.

3. **Which hour of the day had the most requests during the two-week period?**
    - Aggregated the data by hour and identified the hour with the highest number of requests.
    - Plotted a bar chart to visualize the requests by hour.

4. **What percentage of all zeroes during the two-week period occurred on the weekend (Friday at 5 pm to Sunday at 3 am)?**
    - Calculated the total number of zeroes.
    - Identified the number of zeroes that occurred on the weekend and calculated the percentage.
    - Plotted a bar chart to visualize the distribution of zeroes during the weekday vs weekend.

5. **What is the weighted average ratio of completed trips per driver during the two-week period?**
    - Calculated the ratio of completed trips per driver.
    - Computed the weighted average ratio.
    - Plotted a histogram to visualize the distribution of completed trips per driver.

6. **In drafting a driver schedule in terms of 8-hour shifts, when are the busiest 8 consecutive hours over the two week period in terms of unique requests?**
    - Resampled the data in 8-hour intervals and calculated the total number of requests.
    - Identified the busiest 8-hour period.
    - Plotted a line chart to visualize the requests within 8-hour shifts.

7. **True or False: Driver supply always increases when demand increases during the two-week period.**
    - Calculated the difference in requests and unique drivers.
    - Checked if the driver supply always increases with demand.
    - Plotted a scatter plot to visualize the change in requests vs change in driver supply.

8. **In which 72-hour period is the ratio of Zeroes to Eyeballs the highest?**
    - Used a rolling window of 72 hours to calculate the ratio of zeroes to eyeballs.
    - Identified the 72-hour period with the highest ratio.
    - Plotted a line chart to visualize the ratio within a 72-hour rolling window.

9. **If you could add 5 drivers to any single hour of every day during the two-week period, which hour should you add them to?**
    - Aggregated the data by hour and identified the hour with the highest number of requests.
    - Plotted a line chart to highlight the best hour to add drivers.

10. **True or False: There is exactly two weeks of data in this analysis.**
    - Checked the date range to ensure there is exactly two weeks of data.
    - Plotted the number of data points per day.

11. **Looking at the data from all two weeks, which time might make the most sense to consider a true "end day" instead of midnight?**
    - Identified the time when supply and demand are at their natural minimums.
    - Plotted a line chart to visualize total requests and unique drivers by hour of the day.

### Running the Analysis

Run the analysis script to generate the insights and plots:

python analysis.py

### Results

The results of the analysis are presented in the form of printed insights and visualizations. Each question is answered with a corresponding plot to help visualize the findings.

### Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

