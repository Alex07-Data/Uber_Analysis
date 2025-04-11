Uber Trip Data Analysis (September 2014)

This project provides a comprehensive exploratory data analysis (EDA) of over 1 million Uber trips recorded in September 2014. The dataset contains detailed information on pickup dates, times, locations, and Uber base codes.
Dataset Overview

    Total Records: 1,028,136 trips

    Features:

        Date/Time: Timestamp of the trip

        Lat: Latitude of pickup location

        Lon: Longitude of pickup location

        Base: Uber base code associated with the pickup

Data Preparation

The Date/Time column is converted from string format to Python's datetime object for time-series analysis. New columns are derived:

    Day: Day of the month

    Hour: Hour of the day

    Weekday: Day of the week (0 = Monday, 6 = Sunday)
Several histograms were generated to uncover trends in Uber ride demand:
