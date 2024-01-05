# Salary-Inequity-Microsoft-Python-Interview-Question

Given a list of salaries, we'll define a metric called inequity which is the difference between max and min salary seen in the list:

inequity = max(input_list) - min(input_list)

Write a function called min_inequity which takes in a list of salaries, and a value n, and returns the minimum inequity possible when taking n salaries from the full salary list.

Examples:

min_inequity([50000, 100000, 150000, 170000, 30000, 40000, 20000, 90000], 4) = 20000

min_inequity([60000, 80000, 120000, 70000], 2) = 10000
