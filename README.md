# Airbnb Analysis #

This project aims to analyze Airbnb data using MongoDB Atlas, perform data cleaning and preparation, develop interactive geospatial visualizations, and create dynamic plots to gain insights into pricing variations, availability patterns, and location-based trends.

**NAME : Nirmal.K.N**

**BATCH : DW73DW74**

**PROJECT : 4**

## Skills take away From This Project ##

**-> Python scripting** 
**-> Data Collection**
**-> Data Preprocessing**
**-> Visualization**
**-> EDA** 
**-> MongoDB Atlas** 
**-> PowerBI**

## Approach ##

1. Establish a MongoDB connection, retrieve the Airbnb dataset, and ensure efficient data retrieval for analysis.
2. Clean and prepare the dataset, addressing missing values, duplicates, and data type conversions for accurate analysis.
3. Conduct price analysis and visualization, exploring variations based on location, property type, and seasons using dynamic plots and charts.
4. Analyze availability patterns across seasons, visualizing occupancy rates and demand fluctuations using suitable visualizations.
5. Investigate location-based insights by extracting and visualizing data for specific regions or neighborhoods.
6. Create interactive visualizations that enable users to filter and drill down into the data.
7. Build a comprehensive dashboard using Tableau or Power BI, combining various visualizations to present key insights from the analysis.


**Example AIRBNB data structure:**
```
{"_id": "unique_listing_id",
"name": "listing_title",
"description": "listing_description",
"host_id": "unique_host_id",
"host_name": "host_name",
"neighbourhood": "neighbourhood_name",
"location": {
"type": "Point",
"coordinates": [longitude, latitude]
},
"price": "listing_price",
"availability": {
"start_date": "YYYY-MM-DD",
"end_date": "YYYY-MM-DD"
},
"amenities": ["amenity_1", "amenity_2", ...],
"rating": "average_rating",
"reviews": [
{
"reviewer_id": "unique_reviewer_id",
"reviewer_name": "reviewer_name",
"comment": "review_comment",
"rating": "review_rating"
}, ...
], ...
}
```

## Outcome ##

Enhance decision-making skills by enabling stakeholders to make informed choices based on the insights and visualizations provided by the project. Strengthen collaboration and project management skills through the end-to-end development of the project, including task planning, coordination, and timely delivery of project milestones.
