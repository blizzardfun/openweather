# Unit 6 | Assignment - What's the Weather Like?

This Jupyter Notebook will visualize the weather of 500+ cities across the world of varying distance from the equator. Cities are chosen randomly by longitude and latitude. Current weather is used for data. Using scatter plots it will show the folowing relationships
* 1-Temperature (F) vs. Latitude
* 2-Humidity (%) vs. Latitude
* 3-Cloudiness (%) vs. Latitude
* 4-Wind Speed (mph) vs. Latitude

It uses Python Citipy and the OpenWeatherMap API for data
# Plotting
I would have switched to ggplot for a style sheet, but I had already defined my own function for graphing consistency so I wanted to use it. 

# Analysis

From plot 1 it is clear that the temperature is higher closer to the equator. 

In plot 2 I had a data item of 300% humidy which is invalid data. 

The other data in plot 2 shows that it is drier near -20 and +(20-40) latitude than it is at the equator. (information gathered from other sources supports this idea since there is a low pressure band around the equator and high pressure at +-30 degrees) I think there is an indication that it is also drier near the poles, but I am assuming that due to a lack of cities near the poles I have a lack of data to confirm this.

In plot 3 The data is spread rather randomly. There do seem to be horizontal lines in the data. To me that would indicate that there is some rounding done on the data. I would guess that there is some subjectivity to measuring the level of cloudiness resulting in the data grouping around more round values.

Due to the limited data near the poles it is hard to conclude, but it would appear in plot 4 that it is more windy at +60 latitude and moving out toward the poles.