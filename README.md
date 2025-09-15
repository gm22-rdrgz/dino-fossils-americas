## Project Title
**Dino Fossil Mapping & Visualization**

Created: 08/29/2025

## Description
This project maps 500 dinosaur fossil records across the Americas using Folium, 
and includes visualizations with Matplotlib and Seaborn to inpsect diet, taxonomy, 
collection year, and location.

It also demonstrates basic data cleaning and transformation using pandas.

## Features
- Interactive map of fossil locations
- Bar chart for dinosaur diet distribution
- Horizontal Bar Chart for dinosaur fossil counts per family
- A pivot table of dinosaur fossil counts per family by country in the Americas
- Scatter plot to show each collection years
- Data sourced from [The Paleobiology Database](https://paleobiodb.org/#/)

## Libraries
- `pandas`
- `numpy`            (included but not used in this project)
- `matplotlib`
- `matplotlib.pyplot`
- `seaborn`
- `folium`
  
## Notes
The dataset was limited to 500 records for this project for simplicity, but the Paleobiology 
Database allows users to customize the size and scope of their downloads. While numpy was not 
actively used in this project, I often use it in practice projects for basic data cleaning and 
transformation, such as handling null values and performing simple ETL operations. 
I included it here just in case it was needed.

GitHub does not display Folium maps directly in .ipynb files, so I have saved the map as an .html file for viewing. 
Also, I left the collection year as an object data type because some years are sparse, formatted differently, 
or multiple years exist for a single fossil. This approach preserves the integrity of the original records.

I am still in the process of learning python, pandas, and numpy. For this project, I used Matplotlib, 
Seaborn, and Folium for the first time. 

## To view dino_map.html:
- Download the raw file and view it to a browser by double clicking the file
- Download the raw file right click -> "Open with" -> Browser of your choice
- View it right here [dino_map.html](https://gm22-rdrgz.github.io/dino-fossils-americas/dino_map.html)
