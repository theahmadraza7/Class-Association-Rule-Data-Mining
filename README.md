# Class-Association-Rule-Data-Mining

Objective
In this lab, we will explore Class Association Rules (CAR), a type of association rule mining that focuses on
identifying relationships between items in a dataset where a specific target class is defined. We will understand
the concept, its significance, and implement a practical example.
Introduction to Class Association Rules (CAR)
Unlike normal association rule mining, which finds all possible rules in data, Class Association Rules (CAR) target
specific outcomes. CAR is widely used in classification tasks where patterns need to be discovered that strongly
associate with predefined classes.
For example, consider a text document dataset where each document belongs to a predefined category
(Education, Sport, etc.). CAR mining helps discover what terms frequently appear in documents of a particular
category.
Key Concepts
1. Support - Measures how frequently a rule appears in the dataset.
2. Confidence - Indicates the reliability of the rule.
3. Rule-item (condset, y) - A set of items (condset) associated with a target class (y).
4. Apriori Algorithm for CAR - A modification of the Apriori algorithm is used to mine Class
Association Rules.
Example Dataset
Consider the following document dataset:
Applying CAR, we can derive rules such as:
● Student, School ⟶ Education (support = 2/7, confidence = 2/2)
● Game ⟶ Sport (support = 2/7, confidence = 2/3)
