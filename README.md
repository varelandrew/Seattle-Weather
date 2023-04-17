# Seattle, Washington Rain vs. St. Louis, Missouri Rain

X REMOVE # What is the purpose of the project?
- The purpose of the project is to answer the question of whether it rains more in Seattle, WA or St. Louis, MO. Dr. Fischer's parents believe that it rains too much in Seattle and using the provided data sets listed below we are to see if their statement is true or false.

# Description
- The purpose of the project is to answer the question of whether it rains more in Seattle, WA or St. Louis, MO. Dr. Fischer's parents believe that it rains too much in Seattle and using the provided data sets listed below we are to see if their statement is true or false. I will be using python to perform operations that help me towards answering the above question. This includes cleaning up the provided data, and creating visuals to deduce which city has more rain. 
- General conclusions that I discovered from performing the above methods consist of defining what "more rain" means, cleaning up the data sets by removing unused data and filling blank data with relevant data, and creating a few plots to showcase that Seattle has more days of rain but St. Louis has more rain from the days that it does rain. Further and a more in depth conclusion can be viewed at [Communication Document](https://github.com/varelandrew/Seattle-Weather/blob/main/AndrewVarela_Communication_SeattleWeather.pdf) and [Analysis Notebook](https://github.com/varelandrew/Seattle-Weather/blob/main/Andrew_Varela_DATA_3320_Seattle_St_Louis_Analysis_Template.ipynb).

# Requirements
- In order to complete this project I had the help from a few tools. I used Google Colab as a notebook for my code to perform my desired actions when it came to answering the question of this project. Python was my programming language of choice as it has many libraries that make plotting and cleaning up data easy. Finally, I used GitHub as my project storage as it makes it easy to link and store files that I used and created for this project. 

# Data
- The data sets come from this website: [Source of Data](https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND). The website allows you to find past weather and climate data within a specific date range and specific search term like a location. 

# Data Preparation
- What steps did I take to prepare a cleaned up version of the data sets from the website above? 
1. I first imported necessary librarys and loaded the two data sets.
2. I then explored the data sets to see what I was working with and what needed to be cleaned up.
3. First thing I noticed was that the dates needed to be converted to date values instead of string.
4. Then I changed the St. Louis set to only include years 2018 and up as well as data only from the St. Louis Lambert International Airport, so it could match the Seattle data set.
5. I merged the two data frames into a new one that contained precipitation and the dates as the other informtion wasn't relevant to us for this project.
6. I proceeded to tidy up the data set by changing names of columns, combining columns together, and renaming values to make it more clear.
7. Finally I dealt with missing values by adding a number out of 365 that coorelates to each row, as well as a number for month and year for each row. I also found the mean precipitation over the years for each day so I could fill the missing values with the mean value so there were no values missing.
8. I then exported the data into a csv file.

Here you can find the python file that follows these steps I listed: [Data Preparation File](https://github.com/varelandrew/Seattle-Weather/blob/main/Andrew%20Varela%20DATA%203320%20Seattle%20St.%20Louis%20Data%20Preparation%20Template.ipynb)

Here you can find the cleaned csv file: [Clean Data](https://github.com/varelandrew/Seattle-Weather/blob/main/clean_seattle_stl_weather.csv)

# Authors
- The author of this project is Andrew Varela, a 4th year Computer Science major with a minor in Data Science currently attending Seattle University.
- You can find Andrew Varela on [Linkedin](https://www.linkedin.com/in/andrew-varela-a827a71b6/).

# License
- The owner of this project grants permission to use and reuse information from this repository, but does not allow changing of contents in any way.

X REMOVE # Data Analysis
- What steps did I take to analyze the cleaned up data set from the previous steps above?
1. I first imported necessary librarys and loaded the cleaned data set.
2. I then reviewed the contents of the data set to familiarize myself with the data
3. To analyze the data I needed to state a few questions that needed to be answered.
4. Once I figured out what questions needed to be answered I proceeded to plot the data into different visualizations that helped me answer my previous questions.
5. I was then able to finalize my results for a future communication assignment and write a quick conclusion based on my findings.

Here you can find the python file that follows these steps I listed: [Data Analysis File](https://github.com/varelandrew/Seattle-Weather/blob/main/Andrew_Varela_DATA_3320_Seattle_St_Louis_Analysis_Template.ipynb)
