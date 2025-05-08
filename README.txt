
Final Big Data Project: Airbnb NYC with MongoDB

Tools Used:
- MongoDB Compass (GUI for MongoDB)
- Power BI / Tableau for Visualization
- Dataset: NYC Airbnb (48,895 rows, 16 columns)
- Windows 10

Steps:
1. Import `AB_NYC_2019_CLEAN.csv` into MongoDB Compass:
   - Create DB: airbnb_db
   - Create Collection: listings
   - Use 'Import Data' > Choose CSV

2. Data Cleaning:
   - Removed duplicate rows
   - Filled missing 'reviews_per_month' with 0
   - Filled missing 'last_review' with "No Review"
   - Removed listings with price >= $1000 (for clear visualization)

3. Visualizations:
   - Bar Chart: Listings by Borough
   - Histogram: Price Distribution

4. Why MongoDB?
   - Easy to use, works well with JSON/CSV
   - GUI with Compass
   - Great for storing big data documents (like Airbnb listings)

Deliverables Included:
- Cleaned CSV: AB_NYC_2019_CLEAN.csv
- Visuals: listings_by_borough.png, price_distribution.png
- This README.txt (instructions + explanation)

Video Walkthrough (suggested):
- Open Compass and show import
- Query data (e.g., price < 100)
- Open Power BI/Tableau, show visualizations
- Explain project & why MongoDB
