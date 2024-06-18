## London Bike Sharing Dashboard README
## Project Overview
This project involves analyzing and visualizing the London bike-sharing dataset using Python and Tableau. The dataset was sourced from Kaggle and contains detailed information about bike-sharing activities in London. The primary objective was to process and manipulate the data using Python's pandas library, export the cleaned data to an Excel file, and create an interactive dashboard in Tableau with multiple visualizations.

## Dataset
*    Source: Kaggle: London Bike Sharing Dataset
*    File Used: london_bike_final.xlsx (Processed and cleaned version of the original dataset)
  
## Tools and Libraries
1. Python
   
2. pandas: For data exploration, processing, and manipulation
   
3. Tableau: For creating interactive visualizations and dashboards
   
## Data Processing
*    Data Exploration: The dataset was initially explored using pandas to understand its structure and contents.
*    Data Cleaning: Missing values were handled, and necessary transformations were applied to the data.
*    Data Export: The cleaned dataset was exported to an Excel file named london_bike_final.xlsx.
  
## Visualizations
The Tableau dashboard consists of five key visualizations:

1.Total Number of Bike Rides: Displayed on the left side of the dashboard.

2.Moving Average Chart: The main visual on the right side, showing the moving average of bike rides over time.

3.Heat Map: Located under the moving average chart, this visualization depicts the relationship between temperature and wind speed.

4.Tooltips: Two additional visualizations are embedded in the tooltips. When hovering over the heat map or the moving average chart, the following information is displayed:
*    Temperature
*    Wind speed
*    Weather conditions
*    Hour of the day

## Tableau Dashboard Features
1.Interactivity: The dashboard is interactive, allowing users to hover over charts to get detailed information through tooltips.

2.Comparison: Users can compare the total number of bike rides with the moving average, as well as analyze the impact of temperature and wind speed on bike-sharing activities.

## File Structure
data/
london_bike_final.xlsx: The processed and cleaned dataset used for visualization.
notebooks/
data_processing.ipynb: Jupyter Notebook containing the data processing and manipulation code.
dashboard/
London_Bike_Sharing.twb: Tableau workbook file containing the dashboard and visualizations.

## How to Run
Clone the Repository:

git clone https://github.com/yourusername/london-bike-sharing-dashboard.git

Install Dependencies: Ensure you have Python and Jupyter Notebook installed. You can install the required Python libraries using:

pip install pandas

*    Run the Jupyter Notebook: Open the data_processing.ipynb notebook and execute the cells to process the data.
*    Open Tableau: Use Tableau to open the London_Bike_Sharing.twb file and interact with the dashboard.
  
## Conclusion
This project demonstrates the process of data exploration, cleaning, and visualization using Python and Tableau. The interactive dashboard provides insights into bike-sharing patterns in London, influenced by various factors such as temperature and wind speed.

## Acknowledgements
Kaggle for providing the dataset.
The developers of pandas and Tableau for their powerful data analysis and visualization tools.


