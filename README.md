# Developing-data-products
A data product is the production output from a statistical analysis. Data products automate complex analysis tasks or use technology to expand the utility of a data informed model, algorithm or inference.The basics of creating data products using Shiny, R packages, and interactive graphics. This course focuses on the statistical fundamentals of creating a data product.

# Old Faithful Geyser Data Shiny App
This repository contains a simple interactive web application built with R Shiny. The app displays a histogram of the Old Faithful geyser eruption waiting times, allowing users to adjust the number of bins in the histogram via a slider.

Features
Interactive histogram of the Old Faithful geyser waiting times.

Slider input to control the number of bins in the histogram.

Real-time updates to the plot based on user input.

# App Structure
UI: Contains a title, a sidebar with a slider for bin selection, and a main panel displaying the histogram.

Server: Renders the histogram based on the selected number of bins.

# Customization
You can modify the dataset or the plot type by editing the server logic in app.R.

Additional UI controls (e.g., dropdowns, checkboxes) can be added to the sidebar for more interactivity.

# Output result
http://127.0.0.1:3628/
