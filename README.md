# DASHBOARD-DEVELOPMENT

**COMPANY:** CODETECH IT SOLUTIONS

**NAME:** MADHAN G

**INTERN ID:** CT08VCD

**DOMAIN:** DATA ANALYTICS

**DURATION:** 4 WEEKS

**MENTOR:** NEELA SANTHOSH

**Power BI** is a business analytics service by Microsoft. It provides interactive visualizations and business intelligence capabilities with an interface simple enough for end-users to create their own reports and dashboards.

**STEP 1:**
**Connect to Zomato Data:** Import your Zomato data into Power BI Desktop. our file will be in the form of a Excel spreadsheet.
**STEP 2:**
**Data Cleaning and Modeling:**
Ensure data consistency (e.g., standardized city names, cuisine categories).
Create relationships between tables if you have multiple tables (e.g., a "Restaurants" table, a "Cities" table, and a "Cuisines" table).
**STEP 3:**
Creating the Key Metrics (Cards):

**Total Restaurants:**
**Create a "Card" visual.**
Drag the "Restaurant ID" or a similar unique identifier field into the "Fields" area of the card.
Change the aggregation to "Count" or "Count (Distinct)" to get the total number of restaurants.

**Number of Cuisines**:
Create another "Card" visual.
Drag the "Cuisine" field into the "Fields" area.
Change the aggregation to "Count (Distinct)" to get the unique number of cuisines.

**Number of Cities:**
Create a "Card" visual.
Drag the "City" field into the "Fields" area.
Change the aggregation to "Count (Distinct)" to get the unique number of cities.

**Average Rating:**
Create a "Card" visual.
Drag the "Rating" field into the "Fields" area.
Change the aggregation to "Average".

**Adding Slicers for Interactivity:**

**Year Slicer:**
Create a "Slicer" visual.
Drag the "Year" field (if you have it) into the "Fields" area.
Configure the slicer to allow single or multiple selections.

**Country Slicer:**
Create a "Slicer" visual.
Drag the "Country" field into the "Fields" area.
Configure the slicer to allow single or multiple selections.
Slicer Interaction: Ensure that the slicers are correctly interacting with all the visuals on your dashboard.

**Creating Charts:**

**City-wise Restaurant Count (Clustered Bar Chart):**
Create a "Clustered Bar Chart" visual.
Drag the "City" field to the "Axis" area.
Drag the "Restaurant ID" (or a similar field) to the "Values" area, and set the aggregation to "Count."

**Cuisine-wise Restaurant Count (Clustered Bar Chart):**
Create a "Clustered Bar Chart" visual.
Drag the "Cuisine" field to the "Axis" area.
Drag the "Restaurant ID" (or a similar field) to the "Values" area, and set the aggregation to "Count."

**Cuisines and Average Rating (Line Chart):**
Create a "Line Chart" visual.
Drag the "Cuisine" field to the "Axis" area.
Drag the "Restaurant ID" (or a similar field) to the "Values" area, and set the aggregation to "Count."
Drag the "Rating" field to the "Secondary Values" area, and set the aggregation to "Average."

**Table Booking and Online Delivery Percentage (Pie Chart):**
Create a "Pie Chart" visual.
If you have fields like "Has Table Booking" and "Has Online Delivery" (likely with "Yes/No" values), you'll need to create calculated measures to determine the percentage of restaurants with each feature.

Key Considerations:

**Data Quality:** The accuracy of your insights depends on the quality of your Zomato data.
**Performance:** Optimize your data model and visuals for performance, especially with large datasets.
**User Experience:** Design your dashboard with the end-user in mind, making it easy to understand and navigate.

**SAMPLE DASHBOARD**

![SAMPLE DASHBOARD IMAGE](https://github.com/user-attachments/assets/84eeb94d-daf0-4ecc-9b9a-59dbb3a14793)
