# Public Data Interactive Dashboard
## This Application is actually running live on : [Caio's Website](https://cgouvea.com.br)

### This project was never meant to be focused on Front-End development. We're using pre-built Bootstrap templates!

### Objective: Create an interactive Flask web application that allows users to explore and visualize public datasets, such as those available from INEP, SUS, CNES, and others. The website will provide an easy-to-use interface to select different datasets and generate custom dashboards, allowing users to filter the data by region, municipality, and other criteria.

### Main Features

Home Page: The homepage will provide an introduction to the project, explaining the purpose of visualizing and analyzing public data. Caio, the developer, will introduce himself and provide details on how users can navigate through the website's options.

Databases Page: On this page, users will be able to choose the desired dataset (e.g., "Number of Beds in SUS"). Once selected, the user will be redirected to an interactive dashboard that displays the relevant information from that dataset, such as the number of beds, bed types, and other associated data.

Filters and Interactivity: For each dataset, users will be able to apply dynamic filters, such as selecting a municipality or region to view specific data. The dashboard will include charts generated by libraries like Plotly or Matplotlib, enabling clear and interactive data visualizations.

### Technologies Used

Flask: Framework for building the web application's backend.
HTML, CSS, JavaScript: Structuring and styling the user interface.
Plotly / Matplotlib: Libraries for creating interactive charts.
Pandas: For data processing.
Bootstrap: CSS framework for responsive design and UI enhancement.

# Project Phases
### Planning and Requirements Definition:

### Identify the datasets to be used (INEP, SUS, CNES, etc.).
Define the relevant data to be displayed in the dashboards (number of beds, types of beds, municipalities, regions, etc.).
Define the types of filters to be applied (by municipality, region, etc.).
Development Environment Setup:

### Create the basic Flask app structure.
Install necessary dependencies: Flask, Pandas, Plotly, Bootstrap.
Set up the environment to run the app locally.
Home Page (Index) Development:

### Create the HTML template for the homepage with an introduction to the project and a section explaining how to navigate the site.
Add information about the public data available and the project's purpose.
Databases Page Development:

### Create the interface where users can select a dataset.
Display the available dataset options (e.g., "Number of Beds in SUS").
Add logic to redirect users to the corresponding dashboard page once a dataset is selected.
Interactive Dashboard Creation:

### Create a dedicated page to display the dashboard.
Implement interactive charts using Plotly or Matplotlib.
Process the data using Pandas and generate dynamic visualizations.
Implement Filters and Interactivity:

### Add filters for data, such as selecting by municipality, region, or bed type.
Ensure that the selection of filters updates the charts dynamically.
Testing and Validation:

### Test the application locally and across different browsers.
Validate the displayed data and filter functionality.
Future Enhancements:

###Implement features such as exporting charts, generating reports in PDF, etc.
Expand the number of datasets available for visualization.