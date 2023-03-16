# Cacao-Chocolate-Flavors

![Flavors-of-Cacao-Logo-Brown](https://user-images.githubusercontent.com/95665690/225631864-74c1116f-60eb-45d9-a441-881110c43c32.png)


## ABOUT THE DATASET
Chocolate is one of the most popular candies in the world. Each year, residents of the United States collectively eat more than 2.8 billions pounds. However, not all chocolate bars are created equal! This dataset contains expert ratings of over 1,700 individual chocolate bars, along with information on their regional origin, percentage of cocoa, the variety of chocolate bean used and where the beans were grown. The dataset consist of 1795 rows with 9 columns.

## FLAVORS OF CACAO RATING SYSTEM
-	5= Elite (Transcending beyond the ordinary limits)
-	4= Premium (Superior flavor development, character and style)
-	3= Satisfactory(3.0) to praiseworthy(3.75) (well made with special qualities)
-	2= Disappointing (Passable but contains at least one significant flaw)
-	1= Unpleasant (mostly unpalatable)

## BUSINESS QUESTIONS
1.	Where are the best cocoa beans grown?
2.	Which countries produce the highest-rated bars?
3.	What’s the relationship between cocoa solids percentage and rating?

## DATA CLEANING
The data was downloaded from [_Link to Dataset_](https://drive.google.com/drive/folders/158uRE6dxneuEqdXl8-jAJwBDo6lxkMFN) in the form of .csv file and transformed using Microsoft Excel. The following transformations were made using Power Query:

- Fixed common errors regarding the misspelling of countries such as Ecuador and Nicaragua in the company location column.
-	Split cells in the broad bean origin column that contains more than one country into rows to ensure that each cell in that column contains one country only.
-	Fixed names of countries with different spellings e.g. Brazil and Brasil and changed abbreviated names to their full names
-	Finally corrected names of misspelled countries and changed Amsterdam to Netherlands

## SOLUTIONS TO BUSINESS PROBLEMS
1.	To determine where the best cocoa beans are grown, the cocoa percentage and broad bean origin columns were used. From the visualization below, Samoa appeared to be the place where the best cocoa beans are grown with an average cocoa percentage of 85% followed by Peru, Ghana, Central and South America, Caribbean, Belize, Panama, El Salvador, Gabon and Sao Tome as the top 10 places for best cocoa beans.

![image](https://user-images.githubusercontent.com/95665690/225629659-d04a317a-e704-4b60-81f3-0bd60ded3998.png)

2.	Average rating was used to determine which countries produce the highest-rated bars and Chile emerge as the country with the highest-rated bars with an average rating of 3.75 followed by Philippines, Netherlands, Iceland, Vietnam, Canada, Brazil, Poland, Australia and Guatemala as the top 10 places where the highest-rated bars are produced.

![image](https://user-images.githubusercontent.com/95665690/225629980-9cc07c1f-d623-4952-9d3f-d82abbf23917.png)

3.	With a correlation coefficient of 0.0213, it is safe to say that there is very little or no relationship between cocoa solids and rating.

![image](https://user-images.githubusercontent.com/95665690/225630289-7f533ca0-eb2d-4c69-aad5-80ecd9e6506b.png)

### **DASHBOARD**

![image](https://user-images.githubusercontent.com/95665690/225630909-0ebcb67b-babe-44eb-842a-4afe00e745ad.png)





