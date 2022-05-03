# FPGroup30
CS 32 FINAL PROJECT: World Bank Data Country Analysis \
By Annabelle Finlayson, Hope Ha, and Larry Jia. \

Our project takes user input for a country and four World Bank variables and returns background information, statistics, graphs, rankings, and comparable countries and territories.  All statistics are calculated according to World Bank data (https://data.worldbank.org/?most_recent_value_desc=true). We also make use of this csv, https://gist.github.com/radcliff/f09c0f88344a7fcef373, which must be uploaded to the environment, a copy of which is in our github. \ 

There are various improvements that we can make to the current project. We could expand the additional variable options to include all variables in the World Bank database. The Wikipedia scraping also does not return paragraphs for every country because of the different Wikipedia html formatting for different countries, so this function of our project could be improved. The outputs (graphs, dataframes, scraped Wikipedia articles) could be condensed into a PDF format so it is fit for circulation at the World Bank or other policy organization. This would require a greater emphasis on style and document formatting. We could also create heat maps for different variables (and have those heat maps change color over time). 

The ranking block ranks the input countries out of both countries and territories in the World Bank database. We were not able to figure out how to remove every territory from the list. Thus, a possible next step could be to find a way to drop the territories from the dataset.

A limitation within the comparable country and territory code block is that currently if the chosen country has no 2020 data for one of the indicators, it simply drops that indicator from the analysis. Therefore, one next step for the country comparison block code would be to make it possible for the user to choose whether to drop that indicator from the analysis or to conduct the analysis on the most recent year for which data was recorded for all of the chosen indicators. 

