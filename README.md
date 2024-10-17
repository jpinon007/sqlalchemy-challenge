# sqlalchemy-challenge

# Instructions : Create a climate analysis about the area I will be visiting, using Python and SQLAlchemy, and data exploration of my climate database. 

# Solution : I started off by importing necesssary dependencies to run code. In order to relfect tables into SQLAlchemy ORM, I set up Python SQL tooklit and ORM and created an engine to hawaii.sqlite. Next, I reflectd on existing database into a new model and viewed all the classes found on automap. I saved the references to each table and created a session link from Python to the database. In order to review my code, I used my instructor's solution file for reference https://git.bootcampcontent.com/Northwestern-University/NU-VIRT-DATA-PT-06-2024-U-LOLC.git
# Moving on to the precipitation analysis, I was asked to find the most recent date in the data. I then had to create a query to recall the last 12 months of precipitation data and show the results on a plot. Using Pandas plotting, the results were shown on a Matplotlib graph. Next, pandas was used to calculate the summary stats for precipitation. 

# Exploratory Station Analysis: I was asked to create a query that calculated the total number of stations in the data. Next, I designed a query that found the most active stations, listing, and their counts in descending order. Using the most active station id from the last query, I had to calculate the lowest, highest, and avg. temperature. Then, using the most active station id, I was asked to query the last 12 months of temp. observation for the dation and plot my findings on a histogram.
