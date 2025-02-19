# Uber’s most pickups and drop offs in Amsterdam.
## Process
This is a final project for Ironhack data analytics bootcamp. 

I have managed the project using Kanban project management tool inside GitHub. Additionally, i have utilized Python to clean, format and transform the dataset. Further more, i did exploratory data analysis, basic statistics and machine learning using Python. 

Apart from Python, i have used AWS S3 buckets for data storage and Amazon Athena to query data out of the S3 buckets. 

Finally, i have made a dashboard using Tableau public to showcase my findings. (the link will be found at the bottom of this page.)

## What the project does
This project depicts in which area of Amsterdam Uber transport service have been largely requested by riders as well as most drop off locations by areas.  This project also discover which day of the week is the best day for drivers to work and the pick hours for profit maximization.
## Dataset
The dataset i am using is from a volunteer uber driver who work mostly in Amsterdam and it’s surrounding area. He willingly share the data in a pdf format from his personal Uber’s account trips history. From a raw PDF data, i have created 720 rows and 15 columns. I choose sample data randomly from his completed trips from December 01, 2023 to January 31, 2024 from which the driver was 39 days active. 


               Before							             After

![IMG_2686](https://github.com/user-attachments/assets/9f12f835-8d5c-40e6-a816-f1dfcf7dbdd1)








### The contents of the dataset


- Category - Ride options (UberX, Uber Comfort, Uber Black).
- Date_time - The date and time in which the rider is picked.
- Duration - How long the trip takes from A to B.
- Distance in kilometer - The distance from the pickup location to the dropoff.
- Pickup by postcode - The address where the rider is picked up.
- Dropoff by postcode - The address where the rider is dropped off.
- Fare euro - The amount paid by the rider before any deduction.
- Service fee euro - Ubers cut for the app service.
- Tax - Money paid to tax administration.
- Earnings euro - Drivers earning after service fee and tax.
- Third Parties - Payments made to Airport in order to pick from inside the airport.
- Tip - Tips given by riders to the driver.
- Promotion - Extra money paid by Uber to the driver as bonus.
- Hour - Hour of the day in which trips are made.
- Day name - Day of the week in which trips are made.

## Result
The research in this project brings some benefits to the drivers to identify which area and time and day they should focus on targeting in order to maximize their earnings. To make the findings appealing to them, I present an interactive dashboard using tableau public, which gives an insight for anyone who is interested in future decision making.

## Acknowledgements
- I would like to thank the uber driver who volunteer to share his detail data including the financial for this project to happen. 
- I would also like to thank Ironhack stuffs and the teachers for teaching me and my classmates all the skills we need for this project and for the job market.
- Last but not list, i would like to thank me for finishing the bootcamp successfully.


#### Useful links:
- [Here](https://public.tableau.com/views/uberpickupsanddropoffs/PickhoursDash?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) you will find the interactive dashboard on Tableau public.,
- [Here](https://github.com/Biruk-Buye?tab=repositories) You can also check out my other school projects in my github repo
