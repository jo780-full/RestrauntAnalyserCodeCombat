# RestrauntAnalyserCodeCombat

Overview

The Fright Desktop Application is a Python-based desktop application designed for yield testing and sales analysis. The application provides a graphical user interface (GUI) to interact with data related to raw yield testing, cooked yield testing, and sales analysis. It uses the Tkinter library for GUI components and integrates various libraries such as Matplotlib, Pandas, and fbprophet for data analysis and visualization.
Features
1. Raw Yield Testing:
        Allows users to input data related to raw yield testing, including item name, weight, value, and total value.
        Provides functionalities to insert, delete, and update records in the raw yield dataset.
        Enables exporting and importing raw yield data in CSV format.

2. Cooked Yield Testing:
        Facilitates yield calculations for cooked items, considering initial weight, total cost, and price per kilogram.
        Users can input information such as the name of the cooked item, serving weight, and total selling price.
        Provides a "Calculate Yield" button to analyze and display yield-related information.
        Supports sending a detailed email report with yield results.
3. Sales Analysis:
        Offers a sales forecasting feature using the Prophet library, allowing users to analyze and visualize sales data.
        Users can import sales data from a CSV file and receive a sales forecast through email, including graphical representations of the forecast.

4. Database Integration:
        Utilizes a MySQL database to store raw yield testing results and cooked yield analysis information.
        Supports search and manipulation of raw yield data, providing a tree view for easy navigation.
        Enables exporting raw yield data to a CSV file.

5. Graphical User Interface (GUI):
        Intuitive and user-friendly interface with labelled entry fields, buttons, and tree views for data representation.
        Incorporates scrollbars for efficient navigation through datasets.
        Graphical representations of sales forecasts using Matplotlib.

Setup 

    pip install numpy matplotlib pandas fbprophet pymysql 

Database Setup:
    Set up a MySQL database with the required schema (hotel and raw_yeild tables).
    Update the database connection details in the script (host, user, password, etc.).

Email Configuration:
     Provide your email credentials (sender's email, username, password) in the script for email functionalities.


