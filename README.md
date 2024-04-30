# Eat Safe, Love - NoSQL Data Analysis

## Project Overview
The "Eat Safe, Love" project involves exploratory analysis of food establishment hygiene data using NoSQL databases. This analysis aims to identify establishments based on their hygiene scores and ratings, providing insights that can help consumers make safer dining choices.

## Notebook Setup
- This Jupyter notebook is configured to connect to a NoSQL database, where it queries food establishment data.
- The notebook is divided into parts focusing on different aspects of data exploration and manipulation.

## Exploratory Analysis
This section details the analysis performed using MongoDB queries, document counts, and data visualization through Pandas DataFrames. Key questions addressed include:

### 1. Hygiene Score Analysis
- **Query:** Identify establishments with a hygiene score of 20.
- **Method:** Uses `count_documents` to find the number of matching documents and `pprint` to display results.

### 2. London Establishments Rating Analysis
- **Query:** Find establishments in London with a `RatingValue` of 4 or higher.
- **Method:** Results are displayed using DataFrame conversion, showcasing the top entries.

### 3. Proximity and Quality Sorting
- **Query:** Determine the top 5 establishments rated 5 in `RatingValue`, sorted by the lowest hygiene score near the newly added "Penang Flavours."
- **Method:** Utilizes geospatial queries and sorting mechanisms in NoSQL.

### 4. Local Authority Hygiene Failures
- **Query:** Count establishments in each Local Authority area with a hygiene score of 0.
- **Method:** Aggregation and grouping by Local Authority to highlight areas with potential health risks.

# Eat Safe, Love - NoSQL Data Analysis

## Project Overview
The "Eat Safe, Love" project involves exploratory analysis of food establishment hygiene data using NoSQL databases. This analysis aims to identify establishments based on their hygiene scores and ratings, providing insights that can help consumers make safer dining choices.

## Notebook Setup
- This Jupyter notebook is configured to connect to a NoSQL database, where it queries food establishment data.
- The notebook is divided into parts focusing on different aspects of data exploration and manipulation.

## Exploratory Analysis
This section details the analysis performed using MongoDB queries, document counts, and data visualization through Pandas DataFrames. Key questions addressed include:

### 1. Hygiene Score Analysis
- **Query:** Identify establishments with a hygiene score of 20.
- **Method:** Uses `count_documents` to find the number of matching documents and `pprint` to display results.

### 2. London Establishments Rating Analysis
- **Query:** Find establishments in London with a `RatingValue` of 4 or higher.
- **Method:** Results are displayed using DataFrame conversion, showcasing the top entries.

### 3. Proximity and Quality Sorting
- **Query:** Determine the top 5 establishments rated 5 in `RatingValue`, sorted by the lowest hygiene score near the newly added "Penang Flavours."
- **Method:** Utilizes geospatial queries and sorting mechanisms in NoSQL.

### 4. Local Authority Hygiene Failures
- **Query:** Count establishments in each Local Authority area with a hygiene score of 0.
- **Method:** Aggregation and grouping by Local Authority to highlight areas with potential health risks.

## Usage
- To use this notebook, ensure that you have access to a MongoDB database containing the required food establishment data.
- Follow the setup sections to configure your database connection within the notebook.



