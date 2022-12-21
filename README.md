# COVID_tracking
Notebooks and scripts to process public data related to COVID-19

The Dashboard_app folder contains a notebook and data objects for a Shiny app that was deployed at shinyapps.io. The data sources have changed structure and I have archived the application.

The user can select an individual State via the 2-letter code, and one of three counts in the source data. The app displays a running record line graph, a data table, and a Shewhart chart. The Shewhart chart is primarily intended to show trends.

It will throw an error if the entire selected data set is missing.
