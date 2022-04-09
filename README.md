# FPGroup30
CS32 2022 Final Project // Annabelle Finlayson, Hope Ha, Lawrence Jia <br/> 
Our project is to create a data analytics program where a user can upload data, specify what they want done to the data, and then, depending on user input, clean the data (have repeated values removed, separate columns, round values up or down, etc.) and return relevant statistics. If we have time, we could also visualize the data. The steps to complete this task are: <br/> 
1. Get the data from the user (either uploading a file or grabbing it off the web?) and what they want done to the data: cleaning, certain statistics, or analyses <br/> 
2. If necessary, translate spreadsheet data into usable python data <br/> 
3. Perform user inputted cleaning tasks <br/> 
4. Calculate user inputted statistics (i.e. mean, variance, max/min, correlation, regression, etc.) <br/> 
5. Output data visualizations (i.e. scatterplot, histogram, etc.) <br/> 


Updated README: <br/>
Our project scope is to create a data analytics tool that can allow users to submit or scrape datasets (in CSV format) and merge, clean, and analyze. A time-consuming problem for data anlysts and social scientists is to merge different datasets into a clean panel quickly. Our program will merge data according to indexing variables (i.e. country, year, ID #, etc.). We also will have tools to delete repeated values, fill in missing data (extrapolation and interpolation), run correlation matrices, regressions, and summary statistics. If possible, we may explore ways to visualize data or create simulations using the data. <br/>
Code blocks: <br/>
1. Allow user to specify input datasets (using try/except block) OR allow user to specify data source (for instance, World Bank database) <br/>
2. Read dataframe into NumPy (create dataframe that we can later reference and manipulate) <br/>
3. Match variable labels (by country and year) to create a "master" panel dataset (using some kind of match function) <br/>
4. Once master dataset is created, code tools that user can specify to create "edited" dataframes (i.e. dataframe that contains master dataset with interpolated data) <br/>
5. Create code that produces output (i.e. regression results or correlation table in an Excel file) and downlaods to user's machine based on input from user (input(Do you want to run SLS regression?)...input(Please input your y variable: )...input(Please enter your first x variable: ))

