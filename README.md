# 🚲 London Bike Rides
Interactive Dashboards containing Moving average London bike rides from 4 Jan 2015, to 3 Jan 2017 and the user can choose the time period by only dragging and holding the Moving Average pane, also a heatmap showing " Temperature vs wind speed ".
## 📚 About Data

Historical data for bike sharing in London 'Powered by TfL Open Data'

## ✏️ Data Wrangling

Conducted simple data wrangling and data cleaning:
- Renamed the columns to a proper names
- Changed the humidity values to percentage
- Created a season dictionary so that we can map the integers 0-3 to the actual written values
  
  0 spring , 1 summer , 2 fall , 3 winter .
- Created a weather dictionary so that we can map the integers to the actual written values
   
  1 Clear  , 2 scattered clouds, 3 Broken clouds , 4 Cloudy ,  7 Rain , 10 rain with thunderstorm , 26 = snowfall .

📍 Jupyter script: [Notebook](https://github.com/youssufhaddad/London-Bikes-Ride/blob/main/london_bikes.ipynb)

📍 Cleaned Data: [london_bikes_final.xlsx](https://github.com/youssufhaddad/London-Bikes-Ride/blob/main/london_bikes_final.xlsx)

## 📊 Visualization

Produced a 1-pager dashboard using Tableau.

Tableau: [Link](https://public.tableau.com/app/profile/youssuf.haddad3286/viz/LondonBikeRidesDashboard_17108549392220/Dashboard?publish=yes)

![londonbikerides](https://github.com/youssufhaddad/London-Bikes-Ride/assets/139700595/5d53e106-b37a-4ba4-b814-09497f38f96e)




