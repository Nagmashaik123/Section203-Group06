# Term Project : Semantic Analysis of reactions / symptoms of people after taking COVID-19 vaccination
Programmin Steps to be followed.<br/>
Step 1: Extracting tweets - File : Extraction_of_tweets.ipynb # Generate multiple sets of data each user request has 10000 records per one API request.<br/>
Step 2: Extracting Country for each tweet location by calling Geopy API - File : Countries_Cities_Location.ipynb # Processing each set of 10000 records at a time.<br/>
Step 3: Concatinate all the tweets containing each of 10000 records - File : Concatinate_tweets.ipynb. # Combining all files in CovidVaccine.zip to a single file of CovidVaccineWorld.csv<br/>
Step 4: Data cleaning the tweets extracted - File : Data_Cleaning_Tweets.ipynb <br/>
Step 5: Percentage of people who got vaccinated country wide - File : Vaccination_Country_Analysis.ipynb <br/>
Step 6: Vaccination Dosage count from different tweets  - File : Vacc_Dose_TM_Bi-gram.ipynb <br/>
Step 7: Different brands of vaccines identified from topic modelling concepts using monograms from tweets - File : Vacc_Brands_TM_Monograms.ipynb <br/>
Step 8: Different reactions observed in people after getting vaccinated observed data processing on tweets - File : Vaccination_Reactions_Data_Processing.ipynb <br/>


