# Web_Design_Challenge_HM9

# Web Design/Visualization Dashboard (Latitude)

The aim of this project is to create a visualization dashboard website by utilizing visualizations we have developed from the prior homework_6 where [weather data](https://github.com/bigoshunane/Python_API_Challenge_HM6/blob/main/output_data/cities.csv ) was used.

While developing this dashboard web, we will be creating individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. Moreover, there will be a landing page, a page where we can see a comparison of all of the plots and another page where we can view the data used to build them. Dataset was cleaned by using Python and transformed to HTML format.

Web Visualization Dashboard design final output bonus included can be tested clicking on this [link](https://bigoshunane.github.io/Web_Design_Challenge_HM9/Web_Visualizations/landingpage.html)


# Data
[Weather data](https://github.com/bigoshunane/Python_API_Challenge_HM6/blob/main/output_data/cities.csv)

# Tools used
Python (Jupyter notebook), HTML and CSS.

# Visualization : website contents

The website consists of 7 pages total, as shown below;

1. Landing page 

         which shows:
              
           . An explanation of the project.
           . Links to each visualizations page.

![ll](https://user-images.githubusercontent.com/84547558/157135291-e0249df7-e5d2-4815-b07f-19dabb1035b4.png)


![ls](https://user-images.githubusercontent.com/84547558/157135066-214693e5-054f-4874-9c64-70f04a405190.png)


2. Comparisons page 

      that:
                 
        . Contains all of the visualizations on the same page so that we can easily visually compare them.
        . Uses a bootstrap grid for the visualizations.
        . The grid must be two visualizations across on screens medium and larger and one across on extra-small and small screens.
   
 ![cl](https://user-images.githubusercontent.com/84547558/157135814-574df3fa-f1be-4ddc-8061-74249df04daf.png)
  

3. Four Visualization pages: 
                   
        each with:
                    
              . A descriptive title and heading tag.
              . The plot/visualization itself for the selected comparison.
              . A paragraph describing the plot and its significance.
                      
![vl](https://user-images.githubusercontent.com/84547558/157136529-ed227e4a-68ca-4435-bbaa-2492e0a5af61.png)
                  
   
4. Data page:
       
            that;
                 
               . Displays a responsive table containing the data used in the visualizations.
               . The table must be a bootstrap table component.
               . The data must come from exporting the .csv file as HTML, or converting it to HTML. 
                    
![dpl](https://user-images.githubusercontent.com/84547558/157136852-c077b790-1130-4297-a164-5a809975042e.png)

 The website at the top of every page, have a navigation menu that:

  . Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
  
  . Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
  
  . Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
  
  . Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change).                  

# Considerations:

. You may use the weather data or choose another dataset. Alternatively, you may use the included cities dataset and pull the images from the assets folder.

. You must use Bootstrap. This includes using the Bootstrap navbar component for the header on every page, 
  the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.

. You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.

. Be sure to use a CSS media query for the navigation menu.

. Be sure your website works at all window widths/sizes.


# Bonuses:   The web dashboard can be found at [link](https://bigoshunane.github.io/Web_Design_Challenge_HM9/Web_Visualizations/landingpage.html)

. Use a Bootstrap theme to customize your website. You may use a tool like Bootswatch. Make it look snazzy,
  give it some attitude. If using this, be sure you also meet all of the requirements listed above.

. Add extra visualizations! The more comparisons the better.

. Use meaningful glyphicons next to links in the header.

. Have visualization navigation on every visualizations page with an active state. See the screenshot sample below.


![GG](https://user-images.githubusercontent.com/84547558/157310375-0668dc7b-41df-4354-84e5-7d6ee83e1816.png)






Rubric
Unit 11 Rubric - Web Design Homework - Web Visualization Dashboard


References
OpenWeatherMap.org. (2012). Сurrent weather and forecast. Retrieved from https://openweathermap.org/

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
