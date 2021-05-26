# BarcelonaPrice_project

The objective of this project is to study the real estate market in Barcelona, I did web scraping in Barcelona analysing what is the price in different neighbourhoods, and I compared it with lloguer index (is an index which says how much the price of a real state should be depending the area where is it). 

**Presentation: https://public.tableau.com/views/Barcelonaprice/Barcelona?:language=en-GB&:display_count=y&:origin=viz_share_link**

To do it I did:
For Jupyter notebook (Python)- Web Scraping.
Web scraping
1-	Imported all the necessary libraries
2-	Define the information of the webpage
3-	Creating a robot, It consist on a for loop which go for each page of fotocasa getting the information of the real state, it was important to give some time to sleep to the function in order to do a respectful scraping. It is a code which take like 5 hours running because of the amount of real states in Barcelona.
4-	Once we run it, as a result we have a list of list, so he need to separate it (flatten it)
5-	Last step is to export the csv.
Data cleaning
6-	Once we have the csv, I had to clean it, in the file “data_cleaning” are all the steps to clean it. The final result is the file of “fotocasa_clean.csv”, as well as it is in Kaggle platform as “Barcelona_Fotocasa_HousingPrices”.
The function.
7-	In the last step I created a function in which if you introduce your postal code and the number of meter squares of your place, it tells you what is the actual market price of your real state and what it should be depending lloguer index. If you don’t know the size of your home it just give you the price per square meter (€/m²)
8-	To do that I used the csv of fotocasa prices and a file which I got from Barcelona townhall which has the information of lloguer index per district. https://sig.gencat.cat/visors/habitatge.html

For tableau:
9-	It was necessary to download the shape of the districts of Barcelona as a map, I did it using QGIS software.
10-	Once I had the shape of the districts of Barelona as (shp) it is just imported it to tableau to visualize it.

**The result of whole project is a presentation in tableau in which you can see some graphs about the prices of real states in Barcelona depending where are them, if they have terrace, the number of bathrooms…
On the other hand a function which depending where do you live, tells you the actual market price of your place and how much should it cost taking into account the lloguer index.**

![](images/barcelona_price.jpg)
 
