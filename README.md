# machine-learning

Question 1:
Given list of 10 students ages: ages = [19, 22, 19, 24, 20, 25, 26, 24, 25, 24]
 • Sort the list and find the min and max age
        To sort the list of functions we use sort() function 
 • Add the min age and the max age again to the list 
• Find the median age (one middle item or two middle items divided by two) 
• Find the average age (sum of all items divided by their number) 
• Find the range of the ages (max minus min)

# List of student ages
ages = [19, 22, 19, 24, 20, 25, 26, 24, 25, 24]

# Sort the list
ages.sort()

# Find the min and max age
min_age = ages[0]
max_age = ages[-1]

# Add the min and max age to the list again
ages.extend([min_age, max_age])

# Sort the list again after adding min and max ages
ages.sort()

# Find the median age
n = len(ages)
if n % 2 == 0:
    median_age = (ages[n // 2 - 1] + ages[n // 2]) / 2
else:
    median_age = ages[n // 2]

# Find the average age
average_age = sum(ages) / n

# Find the range of the ages
age_range = max_age - min_age

# Print the results
print(f"Sorted ages: {ages}")
print(f"Min age: {min_age}")
print(f"Max age: {max_age}")
print(f"Median age: {median_age}")
print(f"Average age: {average_age:.2f}")
print(f"Range of ages: {age_range}")

Question 2
• Create an empty dictionary called dog 
• Add name, color, breed, legs, age to the dog dictionary 
• Create a student dictionary and add first_name, last_name, gender, age, marital status, skills, country, city and address as keys for the dictionary
• Get the length of the student dictionary 
• Get the value of skills and check the data type, it should be a list 
• Modify the skills values by adding one or two skills 
• Get the dictionary keys as a list 
• Get the dictionary values as a list
