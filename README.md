# settinge.github.io
# Web-Design-Challenge


I created a visualization dashboard website using visualizations I created in https://github.com/settinge/Python-API-s-Challenge.  Specifically, I  plotted [weather data](Resources/cities.csv).

In building this dashboard, I create individual pages for each plot and a means by which they can be navigated. These pages contain the visualizations and their corresponding trends, if any. Also included is a landing page, a page where we can see a comparison of all of the plots, and another page that contains the data used to build them.(https://settinge.github.io/table.html)

### Website Details

The website consisted of 7 pages total, including:

* A [landing page](https://settinge.github.io/Landing.html) containing:
  * An explanation of the project.
  * Links to each visualizations page.
  * Four [visualization pages](https://settinge.github.io/Homework-Visualization-1.html)
                            (https://settinge.github.io/Homework-Visualization-2.html),
                            (https://settinge.github.io/Homework-Visualization-3.html),
                            (https://settinge.github.io/Homework-Visualization-4.html) 

                            each with:

  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](https://settinge.github.io/Comparisons.html) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
* A ["Data" page](https://settinge.github.io/table.html)  that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. 

The website, at the top of every page, has a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries).

Finally, the website was deployed to GitHub pages https://settinge.github.io/index.html.