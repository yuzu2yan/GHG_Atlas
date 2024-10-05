# GHG Atlas
![release_date](https://img.shields.io/badge/release_date-Oct_2024-yellow)
[![python](https://img.shields.io/badge/python-v3.9.2-blue)](https://www.python.org/downloads/release/python-392/)
[![Gradio](https://img.shields.io/badge/Gradio-v4.44.1-blue)](https://www.gradio.app/)   

This is a project of NASA Space Apps Challenge 2024🚀 

<img width="500" alt="space_apps" src="https://github.com/user-attachments/assets/a4601144-dbd4-43fc-afea-4140b9305824">


## Challenge
Use a combination of satellite and model-based datasets to map both human-caused and natural greenhouse gas emissions to enable better understanding of how these emissions contribute to a warmer world.  

### Topic
- Human-caused Emissions
- Natural GHG Sources and Sinks
- Large Emission Events

## Features
It visualizes GHG emissions due to anthropogenic factors and GHG emissions due to natural factors in a given year on a global scale. It also shows the degree of temperature increase between years and illustrates the relationship between these and GHG emissions due to each factor. 

<img width="898" alt="diagram" src="https://github.com/user-attachments/assets/0eeedb64-2ba1-4037-b85e-d4abd014fdeb">

You can search in any language in any region you wish to search, and you can use the scroll bar at the bottom to specify the year. You can also check a checkbox to indicate where CH4 is occurring in large numbers. The map is dynamically updated and has high usability and accessibility.

<img width="700" art="screen" src="https://github.com/user-attachments/assets/4663b889-b063-48de-b930-bbf2149133ed">

## Usage
Open ```src/main.ipynb``` and run the cells in order from the top (download the necessary libraries, if any, as appropriate).

## Software Configuration
Python: Ver.3.9.2    
Gradio: Ver.4.44.1

## Result


## References
[ODIAC Fossil Fuel CO₂ Emissions](https://us-ghg-center.github.io/ghgc-docs/user_data_notebooks/odiac-ffco2-monthgrid-v2023_User_Notebook.html)  
[MiCASA Land Carbon Flux](https://us-ghg-center.github.io/ghgc-docs/user_data_notebooks/micasa-carbonflux-daygrid-v1_User_Notebook.html)  
[EMIT Methane Point Source Plume Complexes](https://us-ghg-center.github.io/ghgc-docs/user_data_notebooks/emit-ch4plume-v1_User_Notebook.html)  
[GISS Surface Temperature Analysis (GISTEMP v4)](https://data.giss.nasa.gov/gistemp/)  
[CarbonTracker CT2022](https://gml.noaa.gov/ccgg/carbontracker/)
