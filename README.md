# codetest


**Interview Task: Application Usage Optimization**

**Task:** 

You are given a CSV file containing information about software application usage within a company. The software (ID 374) can be installed on two computers per user, provided at least one of them is a laptop. 

The CSV file contains the following fields:

- ComputerID
- UserID
- ApplicationID
- ComputerType (Desktop or Laptop)
- Comment

Your task is to write a program that calculates the minimum number of copies of application 374 the company must purchase. 

**Preferred Language:**

Java. However, you may use Python or another language if you are more comfortable with them.

**Requirements:**

1. Your code must correctly calculate the minimum number of copies needed for any given data set.
2. Your solution should handle case-insensitive comparisons (e.g., "Desktop" and "desktop" should be considered the same).
3. The program should ignore duplicate records. Duplicate records have the same ComputerID, UserID, and ApplicationID (regardless of the case of ComputerType or Comment).
4. The program should handle CSV files of varying sizes, ranging from a few records to over a billion records. The program should use a memory-efficient method to handle large files.
5. Include necessary error handling for file not found, and other potential exceptions.
6. Provide an accompanying set of unit tests to ensure the accuracy of your solution.
7. Write your code with production-level quality, considering aspects like readability, maintainability, and performance.

**Deliverables:**

- Source code for the main program.
- Source code for the unit tests.
- A README file explaining how to run your scripts and any other pertinent information.
- A sample output run on a given dataset.

**Bonus:**

- Optimize your solution for speed. You may consider leveraging concurrency or parallel processing techniques.
- Discuss potential scalability challenges and how you would address them in a real-world, production scenario.
