# GroupProject1
1. We gathered, processed, and refined the census data. Our primary examination concentrated on states that experienced the most significant population growth between 2010 and 2020, specifically Washington, Utah, and Texas, alongside those with the least population growth, namely Illinois and Virginia.

2. Subsequently, we cleansed data from Zillow pertaining to residential property sales in these states. We aggregated the annual figures and compared them with the respective population data through graphical representation, as well as conducted a correlation analysis (which we also graphically depicted).

3. The AvgAnnualPrice database was created by manipulating an excel file and extracting the data needed from it gathered from previous data collection.
Some tips to get started would be to make sure that the data you have can be cleaned and to make sure you know what you want to do with the data.
When actually using this data we were able to manipulate it so that we could get a multiple line graph to see trends in the annual price for houses in the states and see how that graph matched with the population change in the states we wanted to focus on. When looking at the graphs it would be a good idea to look at both the databases as well as the graphs to see trends in order to properly analyze everything.


Some issues to note is that last two pull requests had too many conflics, the profesor and Janki coudn't help with it and they suggested to upload a few files manually. This is what we did as it was minutes before the project is due.

4. the rentalvanacny databases were created by downloading CSVs files from FRED national data and mergeing them together. I extracted the data that was necessary, and was inline with the timeframe of census data. When using this data, I was able to manipulate the dataframe so that the columns became rows and rows became columns. This allowed me to merge the data later in the population vs rental graphs. The final result is two databases, one showcasing the % of rental vacancies and the other showing the change between years.

5. the population vs rental vacancy database was created to examine the relationshop between the two. A helpful tip for this section is to store the dataframes from other jupyter notebooks, and loading them at the start, so I did not have to repeat code. This database required some manipulation of the data, including rename of columns, creating new dataframes.
