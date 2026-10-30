# NY-Lottery-Retailers-per-School-District

I determined which school districts had the most licensed NY Lottery retailers. This is in support of my larger capstone project, which is to compare the annual lottery sales from stores located in each school district to the lottery aid each school district ends up receiving.

My process was based on publicly accessible data on the licensed NY Lottery retailers and the school districts. Both datasets had geolocation data, with the school districts having their own polygon geometric shapefile. I determined which school district each retailer belonged to by determining which polygon each point intersected. I did this by using the “.sjoin” function.

40 school districts only had a single NY Lottery retail location while a total of 357 school districts had less than ten retail locations. Broadly speaking, the number of retailers per school district largely correlated with student enrollment. One strong outlier was the Sewanhaka school district, which had the 5th greatest number of retailers (100 retailers) despite having only the school district with the 30th greatest students.
