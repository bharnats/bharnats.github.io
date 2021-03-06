# Web Visualization Dashboard
### Objective:
Create a Web Dashboard Report to show off the plots generated by the [OpenWeather API Interactions](https://github.com/bharnats/API_Interactions-WeatherPy)

Data is more powerful when we share it with others! Used HTML/CSS/Bootstrap and created a visual dashboard to show off the weather analysis charts.Developed individual pages for each plot and a means by which we can navigate between them. These pages contain the visualizations and their corresponding explanations. We also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.


### Visualizations:
The website consists of 7 pages total, including:

* A landing-page containing: https://bharnats.github.io/index.html
  * An explanation of the project.
  * Links to each visualizations page.
  
* Four visualization-pages, 
   * https://bharnats.github.io/Max_Temp_Page.html
   * https://bharnats.github.io/humidity.html
   * https://bharnats.github.io/Cloudiness.html
   * https://bharnats.github.io/wind_speed.html
     * A descriptive title and heading tag.
     * The plot/visualization itself for the selected comparison.
     * A paragraph describing the plot and its significance.


* A Comparisons-page: https://bharnats.github.io/plot_comparison.html
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Used bootstrap grid to customize the website.   
  

* A Data page : https://bharnats.github.io/data.html
  * Displays a responsive table containing the data used in the visualizations.
    * The table used is a bootstrap table component.
    * The data comes from exporting the `.csv` file as HTML, or converting it to HTML. Used a csv-to-html table conversion tool to accomplish this.
    
 The website, at the top of every page, has a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries). The nav has similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

    
Finally, the website is deployed to the GitHub pages!

visit: https://bharnats.github.io/
