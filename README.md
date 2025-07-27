# Website Traffic and Engagement Analysis

This notebook analyzes website traffic and engagement data to understand user behavior and the performance of different marketing channels.

## Data Loading and Cleaning

The data was loaded from a CSV file and cleaned to prepare it for analysis. This included:
- Setting the correct column names using the first row of the data.
- Dropping the redundant first row.
- Converting relevant columns to numeric and datetime data types.
- Extracting the hour of the day from the `DateHour` column.

## Key Findings

### Trends in Sessions and Users Over Time

The plot shows the trend of website sessions and users over time, providing an overview of overall traffic patterns.

### Marketing Channel Performance

- **Total Users by Channel**: A bar plot illustrates the total number of users brought in by each marketing channel, highlighting the most effective channels for user acquisition.
- **Average Engagement Time by Channel**: This bar plot shows the average engagement time per session for each channel, indicating which channels drive more engaged users.
- **Engagement Rate Distribution by Channel**: A box plot visualizes the distribution of engagement rates across different channels, providing insights into the consistency of engagement within each channel.
- **Engaged vs. Non-Engaged Sessions**: A bar plot compares the number of engaged and non-engaged sessions for each channel, showing which channels are more successful in keeping users engaged.

### Peak Traffic Hours

A heatmap displays the traffic volume by hour of the day and channel, identifying peak hours for each channel and overall traffic patterns throughout the day.

### Correlation between Traffic and Engagement

A line plot shows the relationship between engagement rate and sessions over time, helping to understand if high traffic correlates with high engagement.

## Analysis Details

The analysis utilizes the pandas library for data manipulation, matplotlib and seaborn for data visualization, and numpy for numerical operations.

The code cells in the notebook provide the specific steps taken for data cleaning, analysis, and visualization.
