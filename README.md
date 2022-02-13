# IRONHACK week 5 - mid-bootcamp Project

In this project, I tried to analyse the CO2 emissions of a given car pak and compare them with the full market for the given car brands.
Of course, a part of the data (actual license plates of the cars in our park) is confidential and will not be displayed here. I have however created a file with dummies data so that it is possible to see what the original 'CarList' file looked like.

The rest of the data is coming from the RDW opendata website. RDW is the Netherlands Vehicle Authority and it is possible to retrive a lot of information at car level, as cars license plates are visible in their database.
Thanks to this database I have been able to retrieve the official data about the cars in our park, as well as about any car registered by the car manufactuers we work with.

In the end, after cleaning the data, I ended up with two data sets : one with the data about our carpark, one with the data bout all cars registered by the manufacturers on a given period of time.

I have pushed those two data sets as tables in SQL and have retrieved some data from in a second Jupyter notebook, to make my hypothesis testing.
In this hypothesis testing notebook, I check if the average CO2 emissions of our car park are lower than the average of all registrations for the given brands.

I have also used both data sets in Tableau to create visualizations.
Link to the CarPark visualization : https://public.tableau.com/app/profile/ebou6751/viz/Week_5_visu_carpark/Dashboard1#1
Link to the AllRegistrations visualization : https://public.tableau.com/app/profile/ebou6751/viz/Week5_visu_allregistrations/Av_CO22#1
