# GIST 604B – PostGIS

**Student:** Lydia Barker
**Course:** GIST 604B – Open Source GIS
**Module:** Module 4 - Post GIS Database Orchestration
**University of Arizona**

## Project Description
This project workflow began by importing shapefiles and spatial datasets in order to answer questions about geographic areas and populations. Examples of questions answered in this repository are:
- "What is the Asian population in the city of New York?"
- "Approximately how many people live within 50 meters of Queensboro?"

## Tools and Technologies
- PostgresSQL
- PostGIS

## What I Did
- PostGIS Environment set-up for storing and queries of spatial data
- Downloaded a NYC dataset and extracted the data (unzipped) to add to the project's directory
- Imported the spatial data into the PostGIS database
- Tested queries from extracted data

## How to View / Run
- Fork the repository and open it in a GitHub Codespace
- Set up a PostGIS environment in order to store and query the data and enable PostGIS
- Download the sample data by running this command in the terminal: wget https://s3.amazonaws.com/s3.cleverelephant.ca/postgis-workshop-2020.zip
- Unzip the file with this command: unzip postgis-workshop-2020.zip
- Load the unzipped file into your PostGIS database
- Import relevant shaefiles
- Run the queries developed in the sql folder in this repository

## Repository Structure

    .
    ├── README.md
    ├── .devcontainer
    │   ├── devcontainer.json
    │   └── Dockerfile
    ├── sql/
    │   ├── 01_basic_sql_queries.sql
    │   ├── 02_geometry_queries.sql
    │   ├── 03_spatial_relationships.sql
    │   └── 04_spatial_joins.sql
    ├── demos/
    │   ├── demo_aggregation_queries.sql
    │   ├── demo_basic_queries.sql
    │   ├── demo_filtering_queries.sql
    │   └── demo_postgis_queries.sql
    └── docker-compose.yml

