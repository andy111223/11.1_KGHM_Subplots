# KGHM and Copper Price Analysis with Plotly Subplots

## Overview
This project demonstrates an analysis of KGHM and Copper closing prices using interactive visualizations in Python. The author aims to showcase their skills in creating data visualizations, working with time-series data, and effectively using various Python libraries. This analysis specifically utilizes Plotly for interactive plotting and data visualization, making it engaging for recruiters and data science professionals.

## Purpose
The purpose of this project is to demonstrate the following skills:
- Data manipulation and analysis using **Pandas**.
- Creating interactive visualizations using **Plotly** and **Cufflinks**.
- Leveraging **Subplots** to create multiple charts, including line plots and tables in a single view.
- Implementing custom **dark mode themes** for enhanced visualization aesthetics.
- Combining line plots and tables for comparative analysis.
- Formatting and cleaning datetime data for accurate representation in charts.

These skills showcase the author's ability to work with financial data, create interactive plots, and manage multiple visual elements in a single dashboard, which are essential skills for data visualization and analysis roles.

## Features Demonstrated
1. **Libraries Used**:
   - **Pandas**: Data manipulation and preparation.
   - **Plotly**: Interactive plotting with `Scatter`, `Table`, and `make_subplots` features.
   - **Cufflinks**: Offline plotting mode for interactive graphs.

2. **Visualization Types**:
   - **Line Plots**: Closing prices of KGHM and Copper using `go.Scatter()`.
   - **Table**: Comparative closing prices of KGHM and Copper.
   - **Subplots**: Used `make_subplots()` to organize line plots and a table in a three-row layout.

3. **Methods and Techniques Used**:
   - **`make_subplots()`**: Creating a layout with multiple plots in one figure.
   - **`go.Scatter()`**: Creating line plots for KGHM and Copper prices.
   - **`go.Table()`**: Creating a comparison table for KGHM and Copper closing prices.
   - **Custom Layouts**: Added a **dark mode** layout for improved aesthetics using `update_layout()`.
   - **Datetime Formatting**: Converted the datetime index to show only the date without hours using `.strftime("%Y-%m-%d")`.

4. **Interactive Features**:
   - The plots are interactive, allowing for zooming, panning, and hovering over data points for more details.

## Dependencies
This project requires the following dependencies:
- **cufflinks**: 0.17.3
- **numpy**: 1.21.6
- **pandas**: 1.3.5
- **plotly**: 4.14.3

### Install Dependencies
To install the dependencies, use the following command:
```bash
pip install cufflinks==0.17.3 numpy==1.21.6 pandas==1.3.5 plotly==4.14.3
```

### Verify Installed Dependencies
To verify the installed dependencies, use the command below:
```bash
pip list | grep -E "numpy|pandas|plotly|cufflinks"
```

## Cloning the Repository
To clone this project repository, run the following command:
```bash
git clone https://github.com/andy111223/11.1_KGHM_Subplots.git
```

## Usage
The project includes a Jupyter Notebook (`kghm.ipynb`) that walks through the entire analysis process. It visualizes KGHM and Copper closing prices and combines them into a comprehensive dashboard to show comparative insights.

The generated visualizations help understand the trends of KGHM share prices and Copper prices over time and provide a side-by-side comparison with a detailed table.

## Author
I am eager to demonstrate my skills in data visualization, interactive plotting, and Python programming to prospective employers and recruiters. Please explore the visualizations to get a sense of my capabilities in handling and analyzing financial data.

