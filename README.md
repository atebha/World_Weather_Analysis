# World_Weather_Analysis

Purpose:

  Using python code, pandas and API's to perform an analysis of world vacation destinations based on weather, particularly the temperature range at a destination. Python code and the pandas libarary was used to perform an analysis of vacation destinations around the world based on user input minimum and maximum temperature. Using APIs, city locations, based on latitude and longitude coordinates, and nearest hotels to those city locations were found.

Analysis: 

  Starting the analysis, a set of 2000 random latitudes and longitudes coordinates were generated to get the nearest city using an API call with the OpenWeatherMap. This call found 686 cities. Based on that city list, input statements were created to retrieve potential travel destinations based on the user's criteria and nearby hotels based on the nearest cities that were called by the API filtered by the given temperature range inputted by the user. In this case 65-99°F. From the randomly generated list Hawaii was choosen as the destinatoin along with four cities from the archipelago. Those cities were Ahuimanu as the starting and ending city. Hilo, Kahului, and Kapaa were chosen as the travelling cities. The medium of travel between the cities was set as driving, evening if some of the cities had to have a ferry to shuttle you accross with your car. 
  
Challenges:
  
  The heat maps would not generate form the code, this was most likeyl due to the processing time it was taking to run thorugh the API. The second challenged faced was there was an error could from the vacation search when purging the null rows, while this code block still worked the error message was od especially when purging the rows where there were nulls for the hotels in a row such an error message did not pop up. This block of code was refactored from the practice portion on the module. So I suspect the error was due to that as the practice run gave the same error. 
