# Data Visualization Project

## Dataset

The [dataset](https://gist.github.com/ldlinnell/0d00bb3808e2cb97faf8e11c6d0e7ab6) I propose to visualize for my project is the UN data showing intentional homicides and other crimes by either males or females across the globe over certain years. This dataset was originally really disorganized, with some countries only reporting certain years and others not, some reporting some crimes and not others, a constant "according to 100,000 of the population" blocking the code from reading crime type and sex/gender. I've done a lot of work to go through this dataset and make it legible, including adding latitude and longitude and organizing by country, year, crime type, sex/gender, percentage of crimes. This has taken away a lot of time from my actual visualization itself, but overall these edits needed to happen in order to make vizhub able to read my data. 

Here are the edits I made to my dataset, which is 3574 lines long (aka 3,574 lines to edit...) As you can see in the screen shot, I changed each line to the shorter earlier lines, where the original dataset looked like the longer later lines. 
<img width="1254" alt="Proof of Data set change data viz" src="https://user-images.githubusercontent.com/85960143/145550005-a60ada64-73ff-4358-81f6-8ed68e6ddafe.png">


## Prototypes

I’ve created a proof of concept visualization of this data. It's a scatterplot and it shows the number of homicides per year. However, it doesn't show per male and female, or per country.
[![image](https://user-images.githubusercontent.com/85960143/134442128-e7a4113f-f26f-4e33-ab55-b29fbc6065e2.png)](https://vizhub.com/ldlinnell/60291a2c7fbe4bad98417be425f04362)

My first attempt to add my data into the worldmap, after adding latitude and longitude and adjusting ratio size.
[![image](<img width="1438" alt="Screen Shot 2021-12-01 at 10 26 35 PM" src="https://user-images.githubusercontent.com/85960143/144352454-8471545b-b6f8-486a-9fc1-487b75566f43.png">](https://vizhub.com/ldlinnell/9a2c527611fe443481d3fa9c39236568?edit=files&file=index.js&mode=full)

My first attempt at adding a menu to allow people to select a crime type
[![image]<img width="1434" alt="Screen Shot 2021-12-14 at 1 57 41 AM" src="https://user-images.githubusercontent.com/85960143/145948420-0635859f-72c6-4244-af22-2805904b9c24.png">](https://vizhub.com/ldlinnell/9a2c527611fe443481d3fa9c39236568?file=styles.css&mode=full)


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Question 1: How many intentional homicides have been committed against males versus females per each country?
 * Question 2: How many crimes happen per country? What type of crime?
 * Question 3: Does this imply that certain countries there is more violence against women? If so, Which?
 * Question 4: Do the homicide rates change per year? - CHANGE - What are the rates for each type of crime per country in 2017 (the most recent year)? 

## Sketches
[![image](https://user-images.githubusercontent.com/85960143/134443192-fee2e59d-b0e0-4e5d-bd69-84579302c547.png)

This is my main sketch, it shows two different sets of circles, blue and pink for males and females respectively, of different sizes to show the amount of homicides in the area of the circle, so the country. The orange bar at the bottom is a timeline the you should be able to scroll through, however given I only have the data for 2005, 2010, and 2017, maybe three separate interactive tabs would be better.The circles of different colors easily show violence against women versus men in one set country, if the pink circle is bigger on that country, then there have been more intentional murders of women than men. While showing the number of homicides of both males and females with both colored circles. Having the tabs (or timeline) helps answer the question, does it change per year? Maybe also, I could add a clickable interaction on each circle to show the exact numbers (or hover mechanic). 

## Current Project Goal - Updated December 1st

![Sketch of New Data Viz Goal](https://user-images.githubusercontent.com/85960143/144354510-4b04ebd1-951f-42ec-847e-42d4485c2edb.png)

My current goal is to provide a viz that shows the world on a map, and has circles that show crime amount (via size of the dot) with many interactions. I expect to have a menu to switch the maps depending on crime type, as well as switch between male, female, and total (meaning total crime regardless of sex/gender). The circles should be different colors and I will show that on the menu to avoid confusing, for example pink circles for females, blue circles for male, purple circles for total, and then maybe a boldening of the crime type that they are viewing (or maybe a title that appears). This is currently very hopeful and may change. I will focus on the most recent year given in the dataset, 2017.

Sketch:


## Schedule of Deliverables
  The following is a breakdown of tasks I need to complete to achieve my dream of this project:
   
   * Task 1: Fork a viz to a world map - Early October - Done
    ** Try entering my data from my gist - Early October - Done
   * Task 2: Fix dataset! (vizhub struggles to read my data) - Early November
    ** Enter Latitude and longitudes for each country - Done
    ** Organize by gender/sex - Done
    ** Organize by crime type - Done
   * Task 3: Add dots onto the world map - Early November -Done
    ** Purple for total - Done
   * Task 4: Apply a interaction or menu to separate men, women, total, and years - End of November 
    ** People should be able to switch between the map showing pink dots for female, blue dots for males, and purple dots for totals.
    ** Display only the most recent data (2017)
   * Task 5: Apply a hover interaction to show a pop up window that displays crime type statistics(?) or focus on intentional homicides? Or have people select crime type and display those dots. - Early December -

## Open Questions

I have lot of doubts, personally, coding isn't always my strong suit. Specifically, I'm worried about not being able to handle the interactive aspects by myself. I have also been struggling with having vizhub understand my categorical data - such as country. So most of my fear comes from my lack of faith in my own knowledge and ability.
