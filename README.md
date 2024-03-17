# Edmonton-Property-Assessment-Visualization

## Introduction
This project provides a visual representation of property assessments across Edmonton. It features an interactive map that displays properties, highlighting their assessed values and zoning classifications, and a line chart shows assessed values across various years for selected properties.
A pie chart illustrates the distribution of properties within different build year ranges.

## Features
- Interactive map with markers representing properties.
- Ability to click on map markers to view detailed property information.
- Line chart to visualize historical assessed values for a chosen property.
- Selection of zones to filter property data on the map.
- Interactive pie chart displaying property distribution by build year ranges.

## Dataset
The raw dataset can be downloaded from offical database of Edmonton. The project utilizes a dataset named `dataset.csv`, which is the raw data after preprocess. It includes the following fields:
- Property number
- Year assessed
- Latitude and longitude
- Zoning name
- Year built
- Assessed value
- Lot size

## Setup and Installation
To set up the project locally:
1. Ensure you have a modern web browser installed.
2. Clone the repository or download the project files to your local machine.
3. Open the `index.html` file in your web browser to launch the application.

## Usage
Interact with the map to explore property assessments:
- Click on any property marker to get a popup with detailed information.
- Use the dropdown menu to select a specific zone and update the map and pie chart accordingly.
- Double-click a property marker to view the line chart of historical assessed values.

## Technologies Used
- HTML5
- CSS3
- JavaScript
- [Leaflet](https://leafletjs.com/) for interactive maps
- [Chart.js](https://www.chartjs.org/) for dynamic charting

## Contributing
Contributions to the project are welcome. Please fork the repository and submit a pull request with your suggested changes.

## License
This project is open source and available under the [MIT License](LICENSE).

## Contact
For questions and feedback, please contact [Your Name] at [Your Email].
