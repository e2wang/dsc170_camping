# Optimizing Camping Spots with OpenAI and ArcGIS

## Overview
Our project aims to identify optimal camping spots based on user preferences such as
stargazing quality, proximity to forests and roads, availability of facilities, whether
grounds are off-limits due to safety/environmental reasons, etc. We hypothesize that by
combining spatial data analysis with natural language processing, we can create a more
intuitive and user-friendly interface for campers to find their ideal locations. This
question is important as it addresses the growing interest in outdoor activities while
considering environmental sustainability and accessibility.

The target audience for our project includes outdoor enthusiasts, camping planners, and
environmental agencies. By providing a tool that identifies optimal camping locations
based on specific criteria, we can enhance the camping experience, promote
responsible land use, and potentially contribute to the conservation of natural areas.

## Libraries and Modules
- **ArcGis**: For automating ArcGIS operations such as spatial joins and attribute
queries.
- **OpenAI's Python library**: To interface with the OpenAI API for natural language
processing tasks.
- **Pandas/Geopandas**: For data manipulation and integration within the Python
environment.

## Usage
Ensure that OpenAI and the above modules are installed. Initialize OpenAI client with your own API key from `keys.json` and ArcGIS login information from `login.json`. To run the code, use the Jupyter notebook `DSC170_FinalProject_Final.ipynb` which contains Data Cleaning, Analysis, and implementation of OpenAI to find campsites.

## Links
View our project on [ArcGIS Online](https://ucsdonline.maps.arcgis.com/home/group.html?id=624eafed02604b9cb4478af646ab941a#overview)
