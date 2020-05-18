# JRL_test
My fist project
My first project in JRL
_ first presentation

DIAPO 6

I’m going to present you our Qgis work
We’re looking to obtain a map which regroups the evolution of districts between 2000 and 2017 in the USA, and a map of the PADDD in the existing protected areas
Finally we want to regroup all the data to obtain a map that includes all the precedent studied factors

DIAPO 7

For the first stage, we want to identity changes in district in the USA over the studied period
So first, we download the data on a website : us congretional district shapefiles
Then we import the data on Qgis and we obtain different layer of district for each year

DIAPO 8

We want to create only one file which regroups all the evolution of the district between 2000 and 2017
For that, we have to create intersections between the first layer which represents all the 2000 districts and the second layer which represents all the 2002 districts
With that newly created intersections file (between 2000 and 2002), we are going to create a new intersection with the third layer which includes 2004 data
We repeat the operation until 2017 data
With that we can obtain only one file which contains all the data that we want to study in a easier way to analyse them
Do you want me to explain how to make an intersection ? ——> (if the answer is YES) : You have to go in the vectors window, then you open the geoprocessing tool and you select intersection, then you enter the layers with which you want to make the intersection

DIAPO 9

We need to open the « attributate table » of all districts intersects to have the different information we want
To open that table, you right-click on the layer
In the USA, each district can be identified thanks to a national ID and a district number within the state
You will find the name of the state and two variables that corresponds to the above ID
Id2000 gives you the national ID of the district in which the polygon is located in 2000

DIAPO 10

For the second stage we need to download new data and we want to create an overlap with the PA and PADDD data
If some PADDD events happen out of the protected areas, you should redraw the boundaries of the protected areas to reconstitute the boundaries of PA in 2000
We can see that few green dots aren’t in the blue layer which represent PA so we need to create a new file, because that task is difficult, gwenolé gave us the file for the third stage : boundaries of PA in 2000 and the PADDD in the USA since 2000

DIAPO 11

We are going to margin all the files, we have three files : the district intersects in beige, above the boundaries of PA in 2000 in green, and above the PADDD in the USA since 2000 in 
To margin all the files we have to use the « spatial join tools » but it doesn’t work with our files format so I need some help to pursue my work on the data
With the data we have now, we can generate multiple dummies to identify in which areas and which years there have been (lire le diapo)"
