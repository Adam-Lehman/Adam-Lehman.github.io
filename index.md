# Hello, my name is __Adam Lehman__

<h2><span style="color: Gold;">Welcome to my page!</span></h2>
&nbsp;

<img src="img/Backpacking_Photo_ESIIL.jpg" width="750">

## __About Me__

#### I grew up in Middlebury, Indiana and have lived in Colorado for the past 10 years. In 2019, I thru-hiked the Colorado Trail and it was around that time that I discovered the world of GIS. After spending 49 days on trail, I realized how much I love looking at maps and analyzing spatial data. When I got off trail, I began looking at GIS programs. It wasn't until the fall of 2023 that I went back to school due to several reasons, but I am excited to begin a new career. 

#### I am an environmentalist and have a great passion for protecting our planet, so I am excited to be a part of the ESIIL Stars program this summer. I can't wait to further my knowledge of geographic information systems and learn more about earth data science. I have some experience with coding and looking forward to improving those skills over the coming months.
&nbsp;

___

## __Contact Information__ 
#### Email: AdamLehman777@gmail.com
#### LinkedIn: <a href="https://www.linkedin.com/in/adam-lehman777/" target="_blank">Adam-Lehman777</a>
&nbsp;

___

## __Education__
#### <a href="https://www.metrostate.edu/" target="_blank">Metropolitan State University</a>
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - GIS Certificate (2025)
#### <a href="https://www.bsu.edu/" target="_blank">Ball State University</a>
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Bachelors of General Studies with Philosophy and Entrepreneurship Minors (2014)
&nbsp;

___

## __Organizations__
#### <a href="https://www.esri.com/en-us/about/ypn/overview" target="_blank">Esri's Young Professionals Network</a>
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Member (2024 - present)
&nbsp;

___
##__Interships__

### __Environmental Data Science Innovation & Impact Lab (ESIIL)__ 

#### For our project, we analyzed the how changes in climate, population, and agriculture have influenced hydrologic patterns across Colorado. This was an intensive research project with a focus on utilizing Python coding language to perform complicated calculations and produce interactive HTML maps and figures. Database management was a large part of the process and required great attention to detail.

&nbsp;

#### <a href="https://lakevs14.github.io/ESIIL/" target="_blank">Spatiotemporal Trends in Colorado’s Hydrologic Systems</a>

&nbsp;
___

## __Projects__
&nbsp;

<img src="img/SFH Hot Spots.jpg" width="750">

&nbsp;

&nbsp;

#### During the summer of 2019, I hiked the Colorado trail, so I wanted to create a final project for my Cartography class that touched on that experience. For this map, I gathered data from the ArcGIS Online Portal for the mountain peaks, Colorado Trail route, vector layers of the roadways, rivers, and bodies of water. Each layer was then edited to properly display the day in an aesthetic manner. All labels were converted to annotations and placed accordingly, an appropriate color scheme was decided upon, and a hill shade layer was added for depth. Looking back, a cleaner scale should have been used such as 1:280,000 or something of the like.

<img src="img/CT%20%26%2014ers.jpg" alt="Map of CT & 14ers" width="750">

&nbsp;

&nbsp;

#### As is stated in the map, this is a visualization of how interpolation methods produce varying results. Inverse Distance Weighting, Natural (Nearest) Neighbor, and Radial Basis Functions were used to show their differences. 

<img src="img/Precip Totals Central CO - March 2020.jpg" width="750">

&nbsp;

&nbsp;

<img src="img/Skate Park Suitability Layout.jpg" width="750">

&nbsp;

&nbsp;

#### In this project, I downloaded data showing the average amount of snowfall for the Central Colorado Mountains to determine which ski resorts received the most snowfall. The most recent data available was from 2015-2019. I curated the roadmaps with data from the ArcGIS Portal as well as the hillshade layer.

<img src="img/CO Snowfall Ski Resorts.jpg" width="750">

&nbsp;

&nbsp;

<img src="img/NDVI Layout.jpg" width="750"> 
<a href="https://github.com/Adam-Lehman/Adam-Lehman.github.io/raw/main/img/NDVI and Watershed Model (1).svg" target="_blank">
  ModelBuilder Workflow of the Map Above ^
</a>

&nbsp;

&nbsp;

<img src="img/Dam Location Layout.jpg" width="750"> 
<a href="https://github.com/Adam-Lehman/Adam-Lehman.github.io/raw/main/img/NDVI and Watershed Model (1).svg" target="_blank">
  ModelBuilder Workflow of the Map Above ^
</a>

&nbsp;

&nbsp;

<img src="img/Slope Cost Distance Layout.jpg" width="750"> 
<a href="https://github.com/Adam-Lehman/Adam-Lehman.github.io/raw/main/img/Slope Cost Distance Model.svg" target="_blank">
  ModelBuilder Workflow of the Map Above ^
</a>

&nbsp;

&nbsp;

#### For this project, I created a mosaic of 2 DEM raster files collected from the USGS Earth Explorer website. I then combined this information with the shapefile of Chicago, IL communities from the City of Chicago Data Portal to calculate the average elevation for each neighborhood. In the space below the map is a full step-by-step write up of how this map was created and the processes involved. 

<img src="img/Chicago Communities Elevation.jpg" width="750">

[Tutorial - Step by Step Process of a Project](Tutorial%20-%20Step%20by%20Step%20Process%20of%20a%20Project.docx.pdf)

<embed src="Tutorial%20-%20Step%20by%20Step%20Process%20of%20a%20Project.docx.pdf" 
  width="100%" height="500px" type="application/pdf">

&nbsp;

&nbsp;

#### For my Remote Sensing class final project and subsequent presentation slides, I analyzed the Denver Metro Area to see how the vegetation has changed from 1991 to 2023. For this analysis, I gathered data from the USGS Earth Explorer with imagery from Landsat 5 and 8. Great care was taken to ensure the correct bands from each satellite were used to produce correct results as Landsat 5 and 8 have different band designations. 

[Remote Sensing - Denver Vegetation Change - Final Project (PDF)](Remote%20Sensing%20-%20Denver%20Vegetation%20Change%20-%20Final%20Project.pdf)

<embed src="Remote%20Sensing%20-%20Denver%20Vegetation%20Change%20-%20Final%20Project.pdf" width="100%" height="500px" type="application/pdf">


&nbsp;

&nbsp;

<h2><span style="color: orange;">A fun "Wordle" game in Python. Copy this code into Google Colab and play!</span></h2>

&nbsp;

```python

import string

## add color when printing
def prRed(skk): print("\033[91m {}\033[00m" .format(skk))
def prGreen(skk): print("\033[92m {}\033[00m" .format(skk))

#print in bold
def prBold(skk): print("\033[1m{}\033[0m" .format(skk))

## pick a random word from list
import random

def choose_random_word():
    word_list = ['RHYTHMS', 'PYTHONS', 'COURAGE', 'SNOWING', 'MONKEYS', 'TURTLES']
    return random.choice(word_list)

wordleWord = choose_random_word()

# setup of our variables
numOfTries = 7
wordSize = 7
guesses = []
results = []
for i in range(numOfTries):
  guesses.append('')
  results.append('')
order = ['first', 'second', 'third', 'fourth', 'fifth', 'sixth', 'seventh']

## use a for loop to iterate over each try
for guess in range(0,numOfTries):


  ## input the guess and check that it's valid
  validGuess = False
  while not validGuess:
    guesses[guess] = input("What is your "+order[guess]+" guess?").upper()
    ## check if guess is exaclty wordSize characters
    if len(guesses[guess]) == wordSize:
      validGuess = True
    else:
      prRed("Guess must be "+str(wordSize)+" letters. Try again.")
    ## lets check that all wordSize characters are letters
    for letter in guesses[guess]:
      if letter not in string.ascii_uppercase:
        validGuess = False
        prRed("Guess must be all letters. Try again.")

  ## check each letter for existing in wordleWord
  for i in range(len(wordleWord)):
    if guesses[guess][i] == wordleWord[i]:
      results[guess] += wordleWord[i]
    elif guesses[guess][i] in wordleWord:
      results[guess] += guesses[guess][i].lower()
    else:
      results[guess] += '-'

  ## print the previous guesses and results
  for i in range(len(guesses)):
    print(guesses[i], results[i])

  ## check if the user has won
  if results[guess] == wordleWord:
    prBold("Congratulations, YOU WON!")
    break

#Thanks for playing in green
prGreen("Thank you for playing the game.")'''

```

&nbsp;

&nbsp;

<h2><span style="color: orange;">My Programming Final Project</span></h2>

```python

# Import geopandas
import geopandas as gpd

# Install mapclassify
!pip3 install mapclassify

# Install and import contextily
!pip install contextily
import contextily

# Import matplotlib.pyplot
import matplotlib.pyplot as plt
# Import libraries data
libraries = gpd.read_file("https://www.denvergov.org/media/gis/DataCatalog/libraries/shape/libraries.zip")

# Import neighborhood data
neighborhood = gpd.read_file("https://www.denvergov.org/media/gis/DataCatalog/american_community_survey_nbrhd_2016_2020/shape/american_community_survey_nbrhd_2016_2020.zip")

# Creat a spatial join between libraries and neighborhoods
libraries_neighborhood = gpd.sjoin(neighborhood, libraries, how='inner', predicate='contains')

# Calculate the number of libraries in each neighborhood
library_values = libraries_neighborhood.groupby('NBHD_NAME').size()
library_values.name = 'Libraries Per Neighborhood'
library_values = gpd.GeoDataFrame(library_values)

# Merge values of libary_values layer to the neighborhood  data to show the number libraries per neighborhood
all_libraries = neighborhood.merge(library_values, on="NBHD_NAME")

# Define custom colormap
import matplotlib.colors as mcolors
colors = ['lightblue', 'orange']
cmap = mcolors.ListedColormap(colors)

# Plot the number of libraries per neighborhood
# Adjust map size
# Create a legend, set colorscheme, set title
fig, ax = plt.subplots(figsize=(12, 8))
all_libraries.plot(column="Libraries Per Neighborhood", legend=True, edgecolor='black',linewidth=1.3, cmap=cmap, ax=ax)
contextily.add_basemap(ax, crs=all_libraries.crs.to_string())
ax.set_title("Libraries Per Neighborhood")
plt.show()

# Print Libraries Per Neighborhood table
library_values

# Calculate number of people served per library within each neighborhood
all_libraries['People_Served_Per_Library'] = all_libraries['TTL_POPULA'] / all_libraries['Libraries Per Neighborhood']

# Plot the number of people served by each library per neighborhood
fig, ax = plt.subplots(figsize=(12, 8))
all_libraries.plot(column="People_Served_Per_Library", legend=True,edgecolor='black',linewidth=1.3, cmap="Greens", ax=ax)
contextily.add_basemap(ax, crs=all_libraries.crs.to_string())
ax.set_title("People Served Per Library Per Neighborhood")
plt.show()

# Select the relevant columns for the table
library_population_table = all_libraries[['NBHD_NAME', 'People_Served_Per_Library']]

# Display the table
library_population_table

```
___

###### Site Created by Adam Lehman. Last updated on May 20, 2025.
