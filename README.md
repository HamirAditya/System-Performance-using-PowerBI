# System-Performance-using-PowerBI

Overview
This project aims to provide live information about system performance using PowerBI. The system performance data is gathered using Python scripts executed in Spyder from Anaconda distribution. The data includes metrics such as processor speed, memory usage, and network traffic (bytes up and down). The collected data is then stored in a Microsoft SQL Server database for further analysis and visualization in PowerBI.

Components
Python Spyder Scripts: Python scripts are used to collect system performance data. These scripts utilize libraries like psutil and platform to gather information such as processor speed, memory usage, and network traffic.

Anaconda Distribution: Anaconda provides the necessary Python environment and packages for executing the Spyder scripts. It ensures a streamlined setup for data collection.

Microsoft SQL Server Database: The collected system performance data is stored in a Microsoft SQL Server database. This database serves as a centralized repository for the live data.

PowerBI: PowerBI is used to visualize the real-time system performance data. It connects to the SQL Server database to retrieve the live data and presents it in a visually appealing and informative manner.

Usage
Setup Anaconda Environment: Install Anaconda distribution and set up the Python environment with necessary packages like psutil and pyodbc.

Execute Spyder Scripts: Run the Python scripts in Spyder to collect system performance data. Adjust the scripts as needed to customize the metrics being collected.

Configure SQL Server Database: Set up a Microsoft SQL Server database to store the collected data. Create tables to organize the data effectively.

Run PowerBI: Open PowerBI and connect to the SQL Server database where the system performance data is stored. Create visualizations and dashboards to display real-time system performance metrics.

Monitor System Performance: With PowerBI dashboards, monitor the live system performance including processor speed, memory usage, and network traffic.

![perf](https://github.com/HamirAditya/System-Performance-using-PowerBI/assets/160116915/5ef261be-59b8-479f-884d-3c1f075b7e60)

![dff](https://github.com/HamirAditya/System-Performance-using-PowerBI/assets/160116915/bb478aa3-54b5-4d87-b7f5-aed6130cf828)
