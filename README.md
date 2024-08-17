# TripAdvisor Hotel Analysis Dashboard

## Project Overview
This project showcases a Tableau dashboard created to analyze hotel data from Las Vegas. The dashboard provides valuable insights into various aspects of hotel performance, guest demographics, and service offerings, enabling hotel managers, travel agencies, and marketing teams to make data-driven decisions.

## Data Source
The dataset includes information on 21 hotels in Las Vegas, with 504 rows and 24 fields. Key fields in the dataset include:
- Hotel Name
- Number of Rooms
- Hotel Stars
- User Reviews
- User Continent
- Period of Stay
- Additional Services (Free Wi-Fi, Exercise Room, Club, etc.)

## Key Visualizations

### 1. Total Hotels by Stars
A bar chart displaying the distribution of hotels based on their star ratings, providing a clear view of the range of hotel options from luxury to budget.

![Total Hotels by Stars](./path/to/Bar-graph-Total-Hotels-by-Stars.png)

### 2. Total Users by Continent
A bar chart showing the number of users from different continents, offering insights into the geographical distribution of guests.

![Total Users by Continent](./path/to/Bar-graph-Total-Users-by-Continent.png)

### 3. Users by Period of Stay
A circle chart visualizing the distribution of users by their period of stay, highlighting seasonal trends in hotel occupancy.

![Users by Period of Stay](./path/to/Circle-chart-Users-by-Period-of-Stay.png)

### 4. Top 10 Hotels by Total Rooms
A square chart that identifies the top 10 hotels in Las Vegas based on the total number of rooms, indicating which hotels are the largest.

![Top 10 Hotels by Total Rooms](./path/to/Square-chart-Top-10-Hotels-by-Total-Rooms.png)

### 5. Total Hotels by Additional Services
A square chart categorizing hotels based on the additional services they offer, such as free Wi-Fi, exercise rooms, clubs, and basketball courts.

![Total Hotels by Additional Services](./path/to/Square-chart-Total-Hotels-by-Additional-Services.png)

### 6. Traveler Type
A square chart providing insights into the types of travelers staying at the hotels, categorized as Couples, Families, Friends, Business, or Solo travelers.

![Traveler Type](./path/to/Square-chart-Traveler-Type.png)

### Final Dashboard
The final dashboard integrates these visualizations into a cohesive interface, allowing users to explore the data interactively.

![TripAdvisor Dashboard](./path/to/Trip-Advisor-Dashboard.png)

## Project Purpose
The primary purpose of this dashboard is to assist hotel managers, travel agencies, and marketing teams in understanding guest preferences and hotel performance. The insights derived from this dashboard can drive decisions related to hotel services, marketing strategies, and guest experience improvements.

## Stakeholders
- **Hotel Managers:** Optimize services offered based on guest preferences.
- **Travel Agencies:** Tailor packages to meet the demands of various traveler types.
- **Marketing Teams:** Focus on regions with higher user concentration and adjust strategies according to seasonal trends.

## Achievements
- **Enhanced Service Offering:** Identified popular additional services, enabling hotels to enhance guest satisfaction.
- **Targeted Marketing:** Helped identify key regions for focused marketing efforts based on the geographic distribution of users.
- **Seasonal Occupancy Insights:** Provided data on guest stay periods, allowing for better resource allocation during peak seasons.

## Step-by-Step Guide to Building the Dashboard

### 1. Data Preparation
- **Step 1:** Start by importing the dataset into Tableau.
- **Step 2:** Clean and preprocess the data if necessary, ensuring all fields are correctly formatted for analysis.
- **Step 3:** Set up calculated fields if required (e.g., average score, total number of rooms).

### 2. Building Visualizations
- **Step 4:** Create the bar chart for "Total Hotels by Stars."
  - Drag the `Hotel Stars` field to the columns.
  - Drag the `Hotel Name` field to the rows and apply the count function.
  - Customize the chart with colors, labels, and tooltips.

- **Step 5:** Develop the "Total Users by Continent" bar chart.
  - Drag `User Continent` to the columns and the count of `User Country` to the rows.
  - Adjust the axis, labels, and add interactivity with filters.

- **Step 6:** Design the "Users by Period of Stay" circle chart.
  - Use the `Period of Stay` field in the columns and apply the circle mark type.
  - Adjust size and color for better visual representation.

- **Step 7:** Create the "Top 10 Hotels by Total Rooms" square chart.
  - Drag `Hotel Name` to rows and `Number of Rooms` to columns.
  - Sort by descending order and limit to the top 10 hotels.

- **Step 8:** Construct the "Total Hotels by Additional Services" square chart.
  - Use multiple dimensions like `Free Wi-Fi`, `Exercise Room`, etc., in the rows.
  - Count distinct `Hotel Name` for each combination of services.

- **Step 9:** Design the "Traveler Type" square chart.
  - Utilize the `Traveler Type` field in rows and the count of `Traveler Type` in columns.
  - Format the squares based on the total number of travelers in each category.

### 3. Dashboard Integration
- **Step 10:** Drag and drop each worksheet onto a new dashboard in Tableau.
- **Step 11:** Arrange the visualizations logically, ensuring a smooth flow of information.
- **Step 12:** Add interactive filters and ensure the dashboard is fully responsive.

### 4. Final Touches
- **Step 13:** Review the dashboard for consistency in design, font, colors, and interactivity.
- **Step 14:** Test the dashboard with sample data to ensure it meets the project objectives.
- **Step 15:** Publish the dashboard on Tableau Public or export it for stakeholder presentation.


## Conclusion
This Tableau dashboard is a versatile tool for hotel managers, travel agencies, and marketing professionals. It enables data-driven decision-making, ensuring that strategies align with guest preferences and market trends.
