# ae-11-interactive-visualizations


Interactive Visualizations
APPLICATION EXERCISE
In this application exercise we will be studying penguins. The data can be found in the tidycensus and openintro packages. We will use tidyverse and additional packages for making interactive visualizations (ggiraph, plotly, shiny) and maps (leaflet, sf). Lastly, library patchwork is used to show it off.
library(plotly)
library(ggiraph)
library(tidyverse)
library(tidycensus)
library(sf)
library(leaflet)
library(openintro)
library(patchwork)

Part 1: Making Plots Interactive

ggiraph
* Demo: In AE 02 about Houses around Duke we worked with the data dukeforest. If you don’t remember this data, use ?dukeforest. We want to make the above histogram interactive using functions from ggiraph.
* Your turn: Make the scatterplot interactive using functions from ggiraph.
plotly
* Demo: Make the histogram interactive using plotly
* Your turn: Make the scatterplot interactive using functions from plotly.
Part 2: A Shiny Experience
* Demo: We want to setup and launch our first Shiny app using the ShinyServer on campus.
* Your turn: Make the scatterplot interactive using functions from plotly.
Part 3: Maps!
* Your turn: Get a Free Census API Key
* Go to: https://api.census.gov/data/key_signup.html
* Wait for the email
* Then run the chunk. Note that eval is set to false so when you render this chunk will not render again (which is what you want to happen)
* Demo: Pick one or more variables from the sf1 table, then get that census information for a geographical area in 2010.
* Demo: Make a map with the data using the correct geography. Then make it look nice.
* Your turn: Choose your own variables of interest. Try and pick 2 and make sure they are grouped the same. For example, if one is total households you don’t want the other to be total households by race but you might want total households renters.
* Your turn: Make a map with the data using the correct geography. Then make it look nice.
