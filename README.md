# Boston-school-safety
Analysis of crimes around Boston Public Schools to see what school is most at risk of affecting students

First, load the 2021, 2022 & 2023 crime reports files. It is where you can find all the crimes reported by Boston Police. 
Then, you will need to load the Excel file BPS_geolocation where we turned all the School addresses into geolocation we can use for the map.
Finally, the Jupyter Notebook file is where we put everything together,
by concatenating the crime reports files to filter for the different school years; filtering only for offenses related to shootings and,
making sure our data is clean.

There are 2 maps, one for 2022 and one for 2023, but the school year doesn't start in January so we want to make sure we have the right start for the school year.

On the map, there are three things, first, there are the schools with a blue icon and a popup with the name of the school.
Second, we have crimes in red and have a popup displaying the description of the crime, and the date at which the crime occurred. 
Third, we have a blue radius around each school that represent the size of 2 football fields to indicate the crimes inside the radius are close to the schools,
in addition to that it allows us to do some calculation and this is why below the map there is a widget that will display what crimes happened in which school radius,
so we can see which school has had the most crimes within this radius, making also possible a comparison between the 2021-2022 school year. 
