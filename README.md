# SimRacingDashboard

This is a sim racing dashboard aimed at enhancinh sim racers performance by giving more advanced insight of their performance by the use of the API Plotly dash. The dashboard is seperated into two section session info and lap info. Session info provides the sim racer with information regarding the overall performance of a session (up to 20 laps) and the lap info gives insight to a specific lap chosen.

## 1. Session info

- Driver Name - The name of the driver
- Map Name - The name of the map on which the session took place.
- Number of laps - Number of laps the sim racer did during the session
- Car - Car used during the sesion
- Brake Bias - Set Brake Bias
- DRS System - Shows if DRS is enable or not
- Most Improved Lap - The lap with the best improvemnt when compared with the lap before
- Most Improved Time - The time imporoved of the Most Improved Lap
- Times Out Of Track - The number of times the sim racer went out of track bounds
- Average Lap Time - The Average time of all the laps 
- Lap Ranking - A table that ranks all laps together with their time from the fastest to the slowest
- Smoothness Factor - An indicator of how good the performance of the player is for the Throttle, Breaking and Steering
- Number of Times over Optimal Time - How many times the sim racer went above the optimal time for each section, so the sim racers knows in which section he performed the worst

## 2. Lap info

- Table - Shows the time it took to coplete each section together with the optimal time of each section
- Track Map - Displays the map of the track seperated into sections (Stright Lines in yellow and Corners in Pink)
- Choose a Lap - A dropdown menu that allows the sim racers to choose a lap in order to get more advanced insights (see below)
- Tyre temperature - Indicates the average temperature of the tyres in each section
- Select the Straight Line or Corner - A dropdown menu which allows the user to select the section of the chosen lap they want to have more advanced insight on.
- Gas Pedal Usage - The usage of the gas pedal (throttle) during the selected section
- Break Pedal Usage - The usage of the break pedal during the selected section
- Speed - The speed of the car during the selected section
- Front Tyres Slip Angle - The slip angle of the front tyres during the selected section
- Back Tyres Slip Angle - The slip angle of the back tyres during the selected section
- Select a Lap to Compare - A dropdown menu where the sim racer can choose another lap which they want to compare their advanced insights with

## The final version of the dashboard can be seen below. 
![Prototype Final Session](https://user-images.githubusercontent.com/123899208/219104284-81d8f51d-a5b2-42c5-91ed-95de291f0151.png)
![Prototype Final Lap](https://user-images.githubusercontent.com/123899208/219104283-62407c76-a2d7-431d-962c-ead76e90126e.png)
![Prototype Final Technical KPIs](https://user-images.githubusercontent.com/123899208/219104285-c68e44c3-4575-464c-8a8e-082db16001ba.png)
![Prototype Final Comparison](https://user-images.githubusercontent.com/123899208/219104279-8a5882c5-4dc3-4cb6-9134-e12e98f3b422.png)


