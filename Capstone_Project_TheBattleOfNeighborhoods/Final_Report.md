# Capstone Project

## **Brooklyn vs Queens: A Quantitative comparison for new residents**

Having a job in New York City (NYC) and particularly in Manhattan area is
one of the greatest experiences in life and a huge step in one's 
business career as well. Yet, living in a highly populated business center 
as Manhattan is a huge struggle for many of its residents by means of quite 
high rental prices, scarcity in parking places and many other elements of the 
city. This is why two boroughs of NYC, namely Brooklyn and Queens are gaining
popularity as alternative residential areas among newcomers to NYC.[1],[3]

Both of these boroughs are known to offer relatively lower rental prices and 
efficient enough transportation to Manhattan. They are also famous for having
highly diverse multicultural environments, offering their residents spectacular 
views of the iconic skyline of NYC, and a colorful social life with dining places
and nightlife. [1],[2]

Although there are many magazine articles about the comparison of these two boroughs
of NYC, finding a quantitative comparison is very hard to find. Threfore, my project
will be a quantitative comparison of the two areas in terms of venue types and 
their quantities.


[1] https://metropolismoving.com/blog/brooklyn-vs-queens/

[2] https://www.pods.com/blog/2019/03/nyc-moving-guide-the-new-york-city-boroughs-explained/

[3] https://ny.curbed.com/2019/1/29/18200093/move-to-new-york-city-guide-advice


## **Data and Usage**

- The project starts with the comparison of venues categorized under 'Food' section of 
foursquare data. By analyzing the food venues data, I intend to infer about following 
features of communities occupying these boroughs;

    1. **Diversity:** Variety of food venue origins in terms of their cuisine (i.e. African
    restaurant, Chines restaurant, etc.), indicate the diversity of the resident community.
    Therefore, segmentation of food venue types can provide a reasonable measure for
    comparing the diversity levels of Brooklyn and Queens.

    2. **Pace of Life:** Type of food venues in terms of their actual physical structure (i.e. 
    restaurant, food track, etc.) may indicate the life style of residents in the area. 
    At a relatively slow pace area one can expect to have more restaurants/cafes than 
    pizza places or food trucks. 

- Next comparison will be among venues categorized under 'Art and Entartainment' section 
of foursquare data. By analyzing the venues data, I intend to infer about availability 
of social gatherings which will be a measure of strength of social interactions within 
communities of each boroughs.

- Lastly, I would like to compare two boroughs with respect to 'Collage and 
University' venues. Comparison of higher education venues will be a measure of the
average education levels and so may correlate with the acceptance of a newcomer within
the resident community.

## **Data Analysis Results**
Brooklyn and Queens are two well-known neighbors of NYC. (Fig 1). Because of their
proximity I assume traveling to NYC is very similar from any of these boroghs by
public transportation. I also assume populations of each area is not dramatically
different. With these said all data analysis code is stored in the following Jupyter
Notebook;

https://github.com/pekermilas/Coursera_Capstone/blob/master/Capstone_Project_TheBattleOfNeighborhoods/BrooklyVsQueens.ipynb

![NYC Map](NYC_Map.png)
* Fig 1. Geographical locations of Brooklyn neighborhoods (blue circles) and 
Queens neighborhoods (red circles).*

### Analysis of Food Venues
    1. Both Brooklyn and Queens offer variety of cousins by various
    restaurant types. (Fig 2 and Fig 3)
    2. Most common cousins in Brooklyn European and South American originated, while
    in Queens the dominant cousins are more from Asia. (Fig 2)
    3. Number of restaurants are slightly higher in Brooklyn than Queens (about 200). (Fig 3)
    4. In Queens, number of restaurants are very close to the number of non-restaurant
    type food venues (pizza places, food carts, etc.). (Fig 3)
    5. In Brooklyn, there are more non-restaurant type food venues than restaurants. (Fig 3)

![CousinsOfQueensAndBrooklyn](CousinsOfQueensAndBrooklyn.png)
* Fig 2. Most common restaurants by their cousins found in Brooklyn
and in Queens.*

![FoodVenueTypesOfQueensAndBrooklyn](FoodVenueTypesOfQueensAndBrooklyn.png)
* Fig 2. Comparison of types of food venues found in Brooklyn and Queens.*

### Analysis of Arts & Entertainment Venues
    1. Number of Arts and Entertainment venues are much higher in Brooklyn than Queens (106 vs 30). (Fig 4)
    2. While Brooklyn is offering a variety of classic arts based venues such as art galleries
    and concert halls, Queens is mostly offering social gathering places for entertainment such
    as bowling alleys and performing arts venues. (Fig 4)

![ArtPlacesOfQueensAndBrooklyn](ArtPlacesOfQueensAndBrooklyn.png)
* Fig 4. Comparison of Arts and Entertainment venues found in Brooklyn and Queens.*

### Analysis of Higher Education Venues
    1. Number of Education venues in Brooklyn are much highre the number in Queens (54 vs 21). (Fig 5)
    2. Most of the Higher Education venues in Brooklyn are affliated either with a university
    or with a college while ones in Queens half of the venues are not affliated with any 
    university of college. (Fig 5)

![EducationPlacesOfQueensAndBrooklyn](EducationPlacesOfQueensAndBrooklyn.png)
* Fig 5. Comparison of Higher Education venues found in Brooklyn and Queens.*

## **Interpretation of Results and Discussion**

[1] https://github.com/pekermilas/Coursera_Capstone/blob/master/Capstone_Project_TheBattleOfNeighborhoods/Introduction.md
[2] https://github.com/pekermilas/Coursera_Capstone/blob/master/Capstone_Project_TheBattleOfNeighborhoods/NYC_Map.png
[3] 
