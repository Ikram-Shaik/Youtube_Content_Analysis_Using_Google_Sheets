# Youtube_Content_Analysis_Using_Google_Sheets
#### Overview
This project performs an analysis of YouTube video data using **Google Sheets** and an **existing dataset**. The dataset contains information on video performance, categories, channels, and publication dates. The goal is to derive insights from the data and display them on an interactive **dashboard** for easy understanding and decision-making.

#### Features
- **Data Analysis**: Analyzes YouTube video data, including views, categories, and video publishing trends.
- **Dashboard**: A Google Sheets-based dashboard that provides a visual overview of the data.
- **Pre-Defined Questions**: Answers specific questions about the dataset to uncover insights about YouTube content performance.

#### Analysis Questions Solved
This project addresses several key questions to help understand YouTube content trends and performance:

1. **Top 10 Categories with the Highest Number of Views**:
   - Identifies the video categories that generate the most views.
2. **Top 5 Categories with the Highest Number of Videos**:
   - Finds the categories with the most uploaded videos.
3. **Details of the Video with the Highest Number of Views**:
   - Extracts information about the video with the highest view count, including its title and channel.
4. **Average Views for Each Month**:
   - Calculates the average number of views for videos published in each month to identify trends.
5. **Average Views for Each Channel Title**:
   - Computes the average views across different channels, highlighting the most engaging ones.
6. **Sum of Views for Each Category Name**:
   - Aggregates the total views for videos under each category, revealing the most popular types of content.
7. **On Which Date the Maximum Number of Videos is Published**:
   - Determines the specific date when the highest number of videos were uploaded.
8. **Most Watched Channels**:
   - Lists the channels with the most overall views, showcasing the top content creators.

#### How It Works

1. **Data Input**:
   - The analysis is based on an **existing dataset** that includes key columns such as:
     - `Video Title`
     - `Views`
     - `Category`
     - `Channel Name`
     - `Published Date`
   
2. **Data Processing in Google Sheets**:
   - Google Sheets is used to process and filter the dataset.
   - **Formulas** such as `SUM`, `AVERAGE`, `COUNTIF`, and `QUERY` are applied to calculate totals, averages, and rankings.
   
3. **Dashboard Creation**:
   - The data is visualized using **charts** and **pivot tables** within Google Sheets.
   - The dashboard dynamically displays insights based on the pre-defined questions.

#### Setup Instructions

1. **Upload the Dataset**:
   - Import the provided dataset into Google Sheets by opening a new Google Sheet and copying the data into the appropriate columns.

2. **Set Up Data Calculations**:
   - Use Google Sheets formulas to calculate various metrics:
     - **Top Categories**: Use `QUERY` to sort and filter the top categories based on views and video counts.
     - **Average Views per Month**: Apply `AVERAGEIF` or `QUERY` to calculate the average views per month.
   
3. **Create the Dashboard**:
   - Insert charts and pivot tables to visualize the analysis results:
     - Use **Bar Charts** for ranking categories by views and video count.
     - Use **Line Graphs** for monthly trends in average views.
     - **Tables** to display specific details like top channels and videos.
