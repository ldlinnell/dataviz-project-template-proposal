# Data Visualization Project

## Data

The data I propose to visualize for my project is the UN data showing intentional homicides and other crimes by either males or females across the globe over certain years. 

## Prototypes

I’ve created a proof of concept visualization of this data. It's a scatterplot and it shows the number of homicides per year. However, it doesn't show per male and female, or per country.
[![image](https://user-images.githubusercontent.com/85960143/134442128-e7a4113f-f26f-4e33-ab55-b29fbc6065e2.png)](https://vizhub.com/ldlinnell/60291a2c7fbe4bad98417be425f04362)

My first attempt to add my data into the worldmap, after adding latitude and longitude and adjusting ratio size.
[![image](<img width="1438" alt="Screen Shot 2021-12-01 at 10 26 35 PM" src="https://user-images.githubusercontent.com/85960143/144352454-8471545b-b6f8-486a-9fc1-487b75566f43.png">](https://vizhub.com/ldlinnell/9a2c527611fe443481d3fa9c39236568?edit=files&file=index.js&mode=full)


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Question 1: How many intentional homicides have been committed against males versus females per each country?
 * Question 2: Does this imply that certain countries there is more deadly violence against women? If so, Which?
 * Question 3: Do the homicide rates change per year? 

## Sketches
[![image](https://user-images.githubusercontent.com/85960143/134443192-fee2e59d-b0e0-4e5d-bd69-84579302c547.png)

This is my main sketch, it shows two different sets of circles, blue and pink for males and females respectively, of different sizes to show the amount of homicides in the area of the circle, so the country. The orange bar at the bottom is a timeline the you should be able to scroll through, however given I only have the data for 2005, 2010, and 2017, maybe three separate interactive tabs would be better.The circles of different colors easily show violence against women versus men in one set country, if the pink circle is bigger on that country, then there have been more intentional murders of women than men. While showing the number of homicides of both males and females with both colored circles. Having the tabs (or timeline) helps answer the question, does it change per year? Maybe also, I could add a clickable interaction on each circle to show the exact numbers (or hover mechanic). 

## Schedule of Deliverables
  The following is a breakdown of tasks I need to complete to achieve my dream of this project:
   
   * Task 1: Fork a viz to a world map - Early October - Done
    ** Try entering my data from my gist - Early October - Done
   * Task 2: Fix dataset! (vizhub struggles to read my data) - Early November
    ** Enter Latitude and longitudes for each country - Done
    ** Organize by gender/sex
    ** Organize by crime type
   * Task 3: Add dots onto the world map - Early November -Done
    ** Purple for total
   * Task 4: Apply a interaction or menu to separate men, women, total, and years - End of November 
    ** People should be able to switch between the map showing pink dots for female, blue dots for males, and purple dots for totals.
    ** Either add interaction to switch between year, or display only the most recent data (2017)
   * Task 5: Apply a hover interaction to show a pop up window that displays crime type statistics(?) or focus on intentional homicides? Or have people select crime type and display those dots. - Early December

## Open Questions

I have lot of doubts, personally, coding isn't always my strong suit. Specifically, I'm worried about not being able to handle the interactive aspects by myself. I have also been struggling with having vizhub understand my categorical data - such as country. So most of my fear comes from my lack of faith in my own knowledge and ability.
