# LinkedIn-DataMart-Development

## Overview
This project involves building a LinkedIn Data Mart using data engineering techniques. The primary objectives are to parse LinkedIn JSON files, load them into MySQL tables, and create visualizations that utilize the data set. This project aims to familiarize with the data engineering process for provisioning data marts for reporting and analytics purposes.
## Project Structure
The project is divided into several key components:

1. **ETL Process**: Extract, Transform, Load (ETL) process to parse LinkedIn JSON files and load data into MySQL tables.
2. **Database**: Storage of parsed data in a MySQL database.
3. **Visualizations**: Creation of visualizations to explore and analyze the data.
## Project Parts
This project has been completed in two main parts:

1. **Importing LinkedIn Profile Photos**: LinkedIn profile data, including profile photos, is imported in the form of JSON files.
2. **ETL Process**: The imported JSON files are used for the ETL process to load data into MySQL tables and create visualizations.
## Goals

- Parse LinkedIn JSON files and load them into respective MySQL tables.
- Create visualizations using tools like PowerBI or Tableau.
- Implement search capabilities within the visualizations.
## Instructions

### 1. ETL Process

The ETL process involves parsing LinkedIn JSON files located in the `output/profile` folder. The JSON files contain various sections including:

- Demographic information (root level)
- Experiences
- Educations
- Certifications
- Languages
- Honors and Awards
- Publications
- Patents
- Projects
- Volunteers

Each section should be loaded into a separate MySQL table.

### 2. Visualizations

Create visualizations using tools like PowerBI Desktop. The visualizations should include:

- Utilization of profile images from the `output/profile-photo` folder.
- Search capabilities to filter profiles by name, email, or company.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/apurva-p1599/LinkedIn-DataMart-Development.git
   cd LinkedIn-DataMart-Development
   ```
2. **Run the ETL script**:
   Ensure the JSON files are in the `output/profile` folder and run the ETL script to populate the MySQL database.

3. **Load the visualization**:
   Open the visualization file in PowerBI and ensure the data sources are correctly linked to the MySQL database.

## Usage

1. **ETL Process**:
   - Parse and load LinkedIn JSON files into MySQL tables.
   - Use provided Python scripts to automate the process.

2. **Visualizations**:
   - Open the visualization tool (PowerBI or Tableau).
   - Load the visualization file.
   - Explore the data using search functionalities.
