MapReduce-Algorithms-Datascience-Coursera-
==========================================
Inverted Index.py - Below is the problem statement

Create an Inverted index. Given a set of documents, an inverted index is a dictionary where each word is associated with a 
list of the document identifiers in which that word appears.


Relational Join - Problem statment
Implement a relational join as a MapReduce query

Consider the following query:

SELECT * 
FROM Orders, LineItem 
WHERE Order.order_id = LineItem.order_id
Your MapReduce query should produce the same result as this SQL query executed against an appropriate database.

You can consider the two input tables, Order and LineItem, as one big concatenated bag 
of records that will be processed by the map function record by record.

Unique Trims - Problem Statement
Consider a set of key-value pairs where each key is sequence id and each value is a string of nucleotides, 
e.g., GCTTCCGAAATGCTCGAA....

Write a MapReduce query to remove the last 10 characters from each string of nucleotides, then remove any duplicates 
generated.
