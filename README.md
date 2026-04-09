# Olympic-Dashboard-
Aim:
o	Medals Won by gender %

o	Male and female ratios by year

o	Top 5 countries with medals

o	Top Olympic medallists by total medals

o	Total number of participating Countries

o	Total number of sports




Features:
o	ID                                                         
o	Name                                                 
o	Sex                                                      
o	Age                                                      
o	Height                                                
o	Weight                                              
o	Team                                                   
o	Games
o	Year
o	Season
o	City
o	Sport
o	Event
o	Medal







Steps of Transformation of data:
o	In athelete event table, remove games column because year and season are given separately.
o	Remove height and age because they are of no use in our aim.
o	In country definition table, we are given with column heading as column 1, column 2 and column 3 . So,we’ve to rename it  (click on first row and click on “Use first row as heading”).
o	Remove notes column of country definition table because it is of no use.
o	There is NOC column in both table . So, we’ll combine NOC column into one Column of any one table  ( go to home and select “merge queries”. Then, select NOC in merge window then, select  click on arrow and select second table again, click on NOC. Select “full outer” option in joint kind. Then, select ok. Click on the icon present beside country definition column and click on ok. Now remove NOC of athelete event table).
o	Replace column names like: 
	Country definition NOC = Country
	Sex = Gender
	M = Male and F= Female  (Click on M in Gender column then go to transform then on replace value).
o	Check for the null value for each column (click on the icon present beside every column name then check . Country column have a null value click on null and then ok ).

	Medals Won by gender %


      


	Male and female ratios by year
    
     


	 Top 5 countries by medals
 
     

	Top 5 Olympic medallists by total medals
             

	Total number of participating Countries

       
	Total number of sports
                


Overall dashboard:
 

