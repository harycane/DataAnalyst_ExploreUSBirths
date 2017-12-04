# DataAnalyst_ExploreUSBirths
Data Analysis of Birth Dates in US.The raw data behind the story **Some people are too superstitious to have a baby on Friday the 13th**, which you can read here from the [fivethirtyeight article:](https://fivethirtyeight.com/features/some-people-are-too-superstitious-to-have-a-baby-on-friday-the-13th/)

Worked with the dataset from the Centers for Disease Control and Prevention's National Center for Health Statistics. The dataset has the following structure:
year - Year (1994 - 2003)
month - Month (1 - 12)
date_of_month - Day number of the month (1 - 31)
day_of_week - Day of week, where 1 is Monday and 7 is Sunday 
births - Number of births 


- Added descriptive Markdown text
- Read a csv file to a String, split it on newline, removed the header, split each row on comma and converted fields from string to int
- Coded a specific function that returns a dictionary containing the total number of births for each unique day of the week.
- Coded a specific function that returns a dictionary containing the total number of births for each month.
- Coded a generic reusable function that accepts list and column number to return custom dictionary of key value mappings between that column attribute and the total number of births.
