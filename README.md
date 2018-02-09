# Web Visualization Dashboard
**Objective:** 
Create a Web Dashboard Report to show off the plots generated by the [OpenWeather API Interactions](master/edit/bharnats.github.io/bharnats/API_Interactions-WeatherPy)

Data is more powerful when we share it with others! I used HTML/CSS and created a visual dashboard to show off the weather analysis done in my previous project- API_Interactions-WeatherPy

Developed individual pages for each plot and a means by which we can navigate between them. These pages contain the visualizations and their corresponding explanations. We also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.
The website consists of 7 pages total, including:

* A landing-page containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four visualization-pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A Comparisons-page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Used bootstrap grid to customize the website.    
* A Data page(#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table used is a bootstrap table component.
    * The data comes from exporting the `.csv` file as HTML, or converting it to HTML. Used a csv-to-html table conversion tool to accomplish this.
    
Finally, the website is deployed to the GitHub pages!
