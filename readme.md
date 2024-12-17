## NoSQL Databases
---

# NoSQL Database Setup and Analysis

## Table of Contents
- [Description](#description)
- [Data Files](#data-files)
- [Features](#features)
- [Installation](#installation)
- [Results](#results)
- [Author](#author)

---

## Description

This project sets up and analyzes a NoSQL database using MongoDB. The data is sourced from a `JSON` file containing establishments' food hygiene ratings. The project involves:
1. **NoSQL Database Setup** - Configuring and populating a MongoDB database.
2. **Data Analysis** - Querying and analyzing the dataset using Python and MongoDB tools.

The analysis is implemented across two Jupyter Notebooks:
- `NoSQL_setup.ipynb` - For database creation and population.
- `NoSQL_analysis.ipynb` - For querying and exploring the data.

---

## Data Files

| File Name                 | Description                                             |
|---------------------------|---------------------------------------------------------|
| `establishments.json`     | JSON file containing food hygiene rating data.          |
| `NoSQL_setup.ipynb`       | Jupyter Notebook for MongoDB database setup and data loading. |
| `NoSQL_analysis.ipynb`    | Jupyter Notebook for data queries and analysis.         |

---

## Features

1. **MongoDB Database Setup**:
   - Sets up a MongoDB database named `establishments_db`.
   - Imports the `establishments.json` file into a collection.

2. **Data Analysis**:
   - Queries the MongoDB database to analyze food hygiene ratings.
   - Performs queries such as filtering establishments by ratings, location, or business type.

3. **Visualizations**:
   - Generates insightful visualizations (optional) to explore the data.

---

## Installation

1. **Prerequisites**:
- Python 3.x
- MongoDB installed locally or cloud-hosted via MongoDB Atlas
- Jupyter Notebook

#2. **Setup**:
- Clone this repository or download the project files.
     
- Install dependencies (if needed):
```bash
     pip install -r requirements.txt
```
---

## Results

### Key Observations:

1.	Establishments with the highest food hygiene ratings (5) are distributed across various locations.
2.	Business types such as restaurants and cafes dominate the dataset.
3.	Analysis reveals insights into the cleanliness and management confidence of establishments.
---

## Author

**Kendall Burkett**  
https://github.com/KendallBurkett?tab=repositories
 
kbz1987@icloud.com