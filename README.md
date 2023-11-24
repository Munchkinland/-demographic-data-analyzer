# Demographic data analyzer
Demographic Data Analyzer project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/demographic-data-analyzer

Demographic Data Analyzer
This Python script analyzes demographic data from the Adult Income dataset to answer various questions about the population. The dataset includes information about individuals' age, education, occupation, and more.

Function: calculate_demographic_data
The main function, calculate_demographic_data, performs the following analyses:

Number of Each Race:

Calculates the count of each race represented in the dataset.
Average Age of Men:

Calculates the average age of individuals identified as male.
Percentage with Bachelor's Degrees:

Determines the percentage of people with a Bachelor's degree.
Percentage of High Earners by Education:

Calculates the percentage of people with and without advanced education (Bachelors, Masters, or Doctorate) who earn more than 50K.
Minimum Work Hours:

Finds the minimum number of hours a person works per week.
Percentage of Rich Among Those with Minimum Work Hours:

Determines the percentage of people who work the minimum number of hours per week and have a salary of more than 50K.
Country with the Highest Percentage of High Earners:

Identifies the country with the highest percentage of people earning more than 50K.
Most Popular Occupation for High Earners in India:

Determines the most popular occupation among individuals in India who earn more than 50K.

# Load the dataset
df = pd.read_csv('adult.data.csv')

# Calculate demographic data and print the results
calculate_demographic_data(print_data=True)
The function returns a dictionary containing the results of the analyses. You can also choose to print the results by setting print_data to True. The printed results include the number of each race, average age of men, percentage with Bachelor's degrees, and more.

Note: Ensure that the dataset file, 'adult.data.csv,' is in the same directory as the script.
