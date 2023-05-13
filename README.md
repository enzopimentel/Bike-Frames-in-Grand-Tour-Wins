# Performance Analysis of Bike Frames in Professional Cycling Races

This repository contains data and analysis on the performance of bike frames in professional cycling races. The analysis aims to identify the most consistent performing bike frames and explore the financial implications of investing in top-performing frames. The data used in this analysis is sourced from race results of the **Tour de France, Giro d'Italia, and Vuelta a Espana from 2020 to 2022.**

## Data Description
The race results datasets were scraped from firstcycling.com, which provides comprehensive information on professional cycling races. The dataset includes race positions and times for each rider in the selected races. Additionally, data on bike frames and their prices were collected from various sources, including official brand websites and industry publications. The currency conversion from the original currency to Philippine peso was done using Google's conversion rates.

## Tools and Libraries

The analysis was performed using Python and several libraries, including:

- **Jupyter Notebook**: Used for data cleaning, exploration, and analysis.
- **VS Code**: Used with the Jupyter Notebook extension to facilitate a more streamlined and efficient workflow.
- **Python Pandas**: Used for data manipulation and analysis.
- **Beautiful Soup**: Used for web scraping the race results data from _FirstCycling.com_.
- **Datetime**: Used for working with the timestamps in the race results, which required converting them to a standardized format.
- **Power BI**: Used for creating visualizations to better understand the data.

## Analysis
The analysis focuses on two main questions: the most consistent performing bike frames and the cost associated with achieving a podium finish. The performance of different bike frames in the top 3 and top 10 positions across the races from 2020 to 2022 is examined. The average prices of the third-place bikes and the overall top 3 bikes are calculated to determine the financial investment required to achieve a podium finish.

## Implications
The analysis has several implications for different stakeholders in the cycling industry. For professional riders, joining a team sponsored by bike manufacturers such as Specialized or Pinarello can provide a competitive advantage based on their consistent performance in top races. Investors and sponsors can use this information to make informed decisions on supporting teams that use high-performing bike frames. For recreational cyclists, the findings suggest that investing in bike frames from reputable brands like Specialized or Pinarello can enhance their performance in races.

## Limitations
It is important to acknowledge certain limitations in the analysis. The results assume that other factors such as rider skill and team strategy remain constant, and that unforeseen events do not significantly impact race outcomes. Additionally, the analysis focuses on a specific set of races and may not capture the performance of bike frames in other race categories or conditions.

## Data Sources

The following links were used as data sources for this analysis:

- [2022 Tour de France Race Results](https://firstcycling.com/race.php?r=17&y=2022)
- [2022 Giro d'Italia Race Results](https://firstcycling.com/race.php?r=13&y=2022)
- [2022 Vuelta a España Race Results](https://firstcycling.com/race.php?r=23&y=2022)
- [2021 Tour de France Race Results](https://firstcycling.com/race.php?r=17&y=2021)
- [2021 Giro d'Italia Race Results](https://firstcycling.com/race.php?r=13&y=2021)
- [2021 Vuelta a España Race Results](https://firstcycling.com/race.php?r=23&y=2021)
- [2020 Tour de France Race Results](https://firstcycling.com/race.php?r=17&y=2020)
- [2020 Giro d'Italia Race Results](https://firstcycling.com/race.php?r=13&y=2020)
- [2020 Vuelta a España Race Results](https://firstcycling.com/race.php?r=23&y=2020)
- [Tour de France Bikes (BikeRadar)](https://www.bikeradar.com/features/pro-bike/tour-de-france-bikes/)
- [World Tour Bikes 2022 Setups (Bike Room)](https://bike-room.com/blog/world-tour-bikes-2022-set-ups-details-photos-and-insights/)
- [WorldTour Bikes and Tech 2021 (Cyclingnews)](https://www.cyclingnews.com/features/worldtour-bikes-and-tech-whos-using-what-in-2021/)
- [World Tour Pro Team Bikes 2020 (Velon)](https://www.velon.cc/news/2020/2/18/world-tour-pro-team-bikes-2020)
- [List of 2021 UCI WorldTeams and Riders (Wikipedia)](https://en.wikipedia.org/wiki/List_of_2021_UCI_WorldTeams_and_riders#Teams_overview)
- [Pro Bikes of the 2019 Men's WorldTour (CyclingTips)](https://www.cyclingtips.com/2019/01/pro-bikes-of-the-2019-mens-worldtour/)
