# Project Name: Airbnb Listings Filter App

This project provides a simple Streamlit app to interactively filter an Airbnb listings dataframe. The app enables users to apply various filters on the columns of the dataframe and visualize the filtered results.

## Overview

The app uses Streamlit for the user interface and pandas for dataframe manipulation. It allows users to filter columns based on their data types—categorical, numerical, datetime, or text—through an intuitive web interface.

## Features

- **Filter by Categorical Columns**: Choose specific values from a list to filter the dataframe.
- **Filter by Numerical Columns**: Use sliders to set the minimum and maximum values for filtering.
- **Filter by Datetime Columns**: Select a date range to filter entries.
- **Filter by Text Columns**: Enter substrings or regular expressions to match text content.

## How to Use

1. **Run the App**: Start the Streamlit app by running the command:

    ```bash
    streamlit run app.py
    ```

2. **Upload Data**: Load the Airbnb listings dataframe from a CSV file. The example uses a file named `Airbnb_Amsterdam_listings.csv`.

3. **Interact with the UI**: Use the checkboxes and filters provided to refine the dataframe according to your requirements. 

## Installation

Ensure you have Python installed, then install the required packages:

```bash
pip install pandas streamlit
```

## Project Structure

- `app.py`: Main application script containing the Streamlit UI and filtering logic.
- `Airbnb_Amsterdam_listings.csv`: Example dataset used to demonstrate the filtering capabilities.

## Extending the App

Here are some ideas to extend this app:

- **Visualizations**: Integrate charts and graphs using libraries like `matplotlib` or `plotly` to provide visual insights based on filtered data.
- **Export Filtered Data**: Add a feature to download the filtered dataframe as a CSV file.
- **Advanced Filtering**: Include more complex filtering options such as multi-condition filters or custom filter expressions.
- **Integration with Databases**: Connect to a database to fetch data dynamically instead of loading from a CSV file.
