# World_Weather_Analysis

# Module 6

Good thing you got your repo set up and out of the way prior to that kickoff meeting. This project is going to be no joke, but it should be a lot of fun.

At the most fundamental level, Jack needs help answering a question: How might we provide real-time suggestions for our client's ideal hotels? Your first task was to define what you meant by "ideal." So, over the course of the conversation, you narrowed that to hotels that were (1) within a given range of latitude and longitude and that (2) provided the right kind of weather for the client.

When you get back to your desk, your first step is to write out a basic plan for how you'll write code that can do this fairly complex task.

Basic Project Plan
Here's an outline of your project plan:

Task: Collect and analyze weather data across cities worldwide.
Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.
Your analysis of the data will be split into three main parts, or stages.

Collect the Data

Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
Use the citipy module to list the nearest city to the latitudes and longitudes.
Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
Parse the JSON data from the API request.
Collect the following data from the JSON file and add it to a DataFrame:
City, country, and date
Latitude and longitude
Maximum temperature
Humidity
Cloudiness
Wind speed
Exploratory Analysis with Visualization

Create scatter plots of the weather data for the following comparisons:
Latitude versus temperature
Latitude versus humidity
Latitude versus cloudiness
Latitude versus wind speed
Determine the correlations for the following weather data:
Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed
Create a series of heatmaps using the Google Maps and Places API that showcases the following:
Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed
Visualize Travel Data

Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:

Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
Create a heatmap for the new DataFrame.
Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
Store the name of the first hotel in the DataFrame.
Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.

Your project planning document is prepared, approved, and pinned above your computer. You're ready to get going on the first step: creating a list of over 1,500 latitudes and longitudes.

...

But wait. Which one runs north to south? Latitude or longitude? And which one runs east to west? And how exactly do these work, again? As a professional in the world of data, you are no stranger to employing Google-fu when faced with a problem, so you decide to do a quick self-taught review.


After exporting your CSV file, you closed your laptop and headed home, confident in a good day's work.

And, when you come into work the next day, you hear that someone else has been impressed with your work as well—Jack! In fact, Jack is so impressed that he wants to give you the opportunity to take the day to dedicate some time to a different project: creating a community outreach website for middle school STEM students.

This is an exciting project. These community-focused opportunities don't come around as often as you would like, and they are a great chance to get kids involved in STEM. Additionally, you work with other tech companies in the area, each taking on one aspect of the project.

Your company is going to focus on climate change, and since you know how to use Matplotlib, you decide to create some visualizations that showcase the weather parameters you retrieved with changing latitude for the 500-plus cities from all over the world. The students will then be able to use these visualizations to explore how weather parameters change based on latitude.

---

We are going to create a series of scatter plots for each weather parameter against the latitude for all the cities. The students will use these scatter plots to write a summary report on how different weather parameters change based on the latitude.

We'll create scatter plots for latitude vs. maximum temperature, humidity, cloudiness, and wind speed. The first, latitude vs. maximum temperature, should look like the following scatter plot.

---

Jack loves your work on the scatter plots thus far, and the other tech companies were impressed, too. They ask you to put together something that can help the students explore how to determine correlations between weather data and latitude.

You and Jack decide to divide and conquer this task. He will write the piece on the scientific method and describe how to use linear regression on the scatter plots. You volunteer to use your scatter plot skills to create scatter plots for each weather parameter on the Northern and Southern Hemispheres. You'll need to also add a regression line equation and correlation coefficient to each scatter plot, so your first step is to brush up on linear regression. You know this is something Jack uses regularly, so you'll need to really understand it if you want to continue impressing the team.

---

Now that you are familiar with generating linear regression lines and equations, you can put this knowledge to work by generating a regression line for latitude and maximum temperature for the Northern and Southern Hemispheres.

You send Jack a quick text to let him know you'll be back to APIs soon—and you're excited to fill him in on what you've learned about this side project.

---


