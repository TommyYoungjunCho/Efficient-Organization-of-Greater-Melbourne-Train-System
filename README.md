# Efficient Organization of Greater Melbourne Train System

**Project Overview**

This project investigates how the greater Melbourne train system could be organized more efficiently to better suit public usage, particularly during rush hour. By analyzing train usage data, population demographics, and building usage, the project aims to propose the implementation of express train lines to enhance commuter efficiency and reduce road traffic, thereby contributing to liveability, inclusiveness, health, and sustainability.

**Technologies Used**

- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Geopandas
- **Tools**: Jupyter Notebook, GitHub

**Project Achievements**

- **Effective Data Integration**:
    - Successfully integrated multiple datasets to provide a comprehensive analysis of train usage, population, and building data.
- **Insightful Visualizations**:
    - Developed detailed map visualizations to identify key regions for express train lines, facilitating better decision-making.
- **Practical Recommendations**:
    - Proposed specific express train lines that could improve commuter efficiency and reduce environmental impact.

**Period**

- 2021.3 ~ 2021.6

**GitHub Repository**

- https://github.com/TommyYoungjunCho/Efficient-Organization-of-Greater-Melbourne-Train-System

# Project Details

---

1. **Data Description**:
    - **Metro Train Station Patronage**: Usage data from 2005 to 2019.
    - **Metro Stations Accessibility**: Latitudinal and longitudinal coordinates of each station.
    - **Census Data**: Population data of Melbourne’s local government regions.
    - **Australian Postcodes**: Regional locational data.
    - **Building Usage Data**: Data on building usage by suburb and coordinate location.
    
2. **Data Exploration and Preprocessing**:
    - **Patronage Data**: Excluded the 2012-13 column due to missing values, aggregated data by region using the mean function.
    - **Metro Stations Accessibility**: Cleaned coordinate data and merged with patronage data.
    - **Australian Postcodes**: Extracted data for Victorian postcodes, combined regions, and cleaned regional names to match census data.
    - **Census Data**: Cleaned and merged with postcode data to create a combined dataset for population analysis.
    - **Building Usage Data**: Extracted data representing office usage to visualize locational data.
    
3. **Machine Learning Models**:
    - **Data Visualization**: Created map visualizations to represent train station patronage, population distribution, and office locations. This helped identify regions with high patronage and population density.
    - **Express Line Visualization**: Developed the `get_map_line` function to visualize proposed express train lines on the map.
    
4. **Results and Discussion**:
    - **Train Station Patronage**: Identified that regions like Caulfield, Northern, and Burnley had the highest patronage, indicating potential targets for express lines.
    - **Population and Office Distribution**: Found that office use is predominantly around the CBD, while residential population is highest in eastern suburbs, suggesting a need for efficient train connectivity in these areas.
    - **Proposed Express Lines**: Suggested express train lines connecting major stations with high patronage and population density to the CBD, aiming to reduce commute times and alleviate road traffic.
    
5. **Proposed Solutions**:
    - **Yellow Line**: Stops at Dandenong, Springvale, Clayton, Huntingdale, Oakleigh, Caulfield, and South Yarra.
    - **Red Line**: Stops at Ringwood, Box Hill, Camberwell, Glenferrie, and Richmond.
    - **Blue Line**: Stops at Sunshine and Footscray.
    - **Purple Line**: Stops at Werribee, Hoppers Crossing, Williams Landing, and Newport.
    - **Green Line**: Inner-city loop connecting Southern Cross, Flinders Street, Parliament, Melbourne Central, and Flagstaff.

## Notion Portfolio Page
- [[Notion Portfolio Page Link](https://magic-taleggio-e52.notion.site/Portfolio-705d90d52e4e451488fb20e3d6653d3b)](#) 
