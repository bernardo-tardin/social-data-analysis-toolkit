# People Data Analysis and Visualization Toolkit
This project is a Python-based toolkit for performing data analysis and visualization on a JSON dataset of individuals. It also includes a separate, general-purpose GUI File Viewer for browsing and editing text-based files.

## Features
This repository contains two main components:

1. **Data Analysis & Management Library**

    A collection of Python functions designed to work with a dataset.json file containing profiles of individuals.

  * **Data Handling (CRUD)** 💾

    * Load and parse the main JSON database.

    * Add new individuals to the database.

    * Save changes back to the JSON file.

    * (Stub for updating existing records is included).

  * **Querying and Searching** 🔍

    * Find individuals by name.

    * Look up a person by their BI or CC (Portuguese ID numbers).

    * Filter individuals by their religion or pets.

  * **Data Aggregation & Analysis** 📊

    * Calculate the distribution of individuals across different professions.

    * Generate a list of the Top 10 most popular sports.

    * Create an index of all animals and the people who own them.

    * Get a total count of all individuals in the database.

  * **Data Visualization** 📈

    * Generate and display a bar chart showing the distribution of professions.

    * Generate and display a bar chart for the Top 10 sports.

2. **File Viewer GUI**

    A standalone desktop application built with PySimpleGUI.

    * File System Browser: Navigate your local folders.

    * File Filtering: Automatically lists common text-based files (.txt, .csv, .json, .py).

    * View & Edit: Open any selected file, view its contents in a text box, and make edits.

    * Save Functionality: Save any changes you make directly back to the file.
