""" Clear the screen before running or restarting the script. """
# for windows
# for mac and linux

"""
Asks user to specify a city, month, and day to analyze.

Returns:
    (str) city - name of the city to analyze
    (str) month - name of the month to filter by, or "all" to apply no month filter
    (str) day - name of the day of week to filter by, or "all" to apply no day filter
"""

# City selection
# valid selection list

# Input validation

# time filter selection
# valid selection list

# lists of the valid months and days values

# none filter

# both filter
# month selection
# Input validation

# day selection
# Input validation

# month filter

# day filter

"""
Loads data for the specified city and filters by month and day if applicable.

Args:
    (str) city - name of the city to analyze
    (str) month - name of the month to filter by, or "all" to apply no month filter
    (str) day - name of the day of week to filter by, or "all" to apply no day filter
Returns:
    df - Pandas DataFrame containing city data filtered by month and day
"""

# load data file into a dataframe

# converting the 'Start Time' column to a datetime

# creating new columns 'Month' & 'Day'

# Filter by month if applicable
# New dataframe filtered by month

# Filter by day of week if applicable
# New dataframe filtered by day

"""Displays statistics on the most frequent times of travel."""

# most common month

# most common day

# create an hour column from the 'Start Time' column

# most common start hour

"""Displays statistics on the most popular stations and trip."""

# most commonly used start station

# most commonly used end station

# most frequent combination of start station and end station trip

"""Displays statistics on the total and average trip duration."""

# Time conversion constants

# total travel time

# Time conversion

# printing converted time

# Mean time travel

"""Displays statistics on bikeshare users."""

# Counts of user types

# counts of gender

# Display earliest, most recent, and most common year of birth


"""
The function takes the city name from get_filters function as input 
and returns the raw data of that city by chunks of 5 rows.

Args:
    (str) city - name of the city to return the raw data.
Returns:
    df - raw data of that city by chunks of 5 rows.
"""

# Raw data is available to check
