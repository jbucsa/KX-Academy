[![LinkedIn][linkedin-shield]][linkedin-url-Bucsa]

# KDB Developer Level 2 Course

## Description

### Course Overview

Welcome to the KDB Developer Level 2 Course!

This lesson will give you an overview of what to expect in this introductory course:

1. Atoms & Primitives
   - Introduction to Atoms & Primitives
     - Vectors/Lists
     - Atoms
   - Datatypes
     - How to use the type command
     - Temporal datatypes
     - Textual datatypes
     - Nulls and Infinite values
   - Primitives
     - Basic Primitives
     - Operator Precedence
     - Comparison Primitives
     - Function notation
   - Variables & Assignment
     -  Variable Assignment
     -  Using Variables in Arithmetic Operations
     -  Assignment and Projecting Functions
2. Lists 
   - Introduction to Lists
     - Simple Lists
     - General Lists
   - List Creation
     - Creating lists from atoms
     - Generating lists
     - Joining lists
   - List Indexing & Access
     - List indexing
     - Indexing Lists at Depth
     - Index Elision
   - List Manipulation & Comparison
     - List Manipulation
       - Subsetting lists
       - Finding items in lists
       - Analysing lists
     - List Comparison
   - List Amendment
     - Amendment by Indexing
     - Amendment using @
     - Amendment using .
3. String Manipulation
   - Introduction to Strings
     - Creating and printing strings
     - Displaying Output
   - String Manipulation
     - Cutting/creating strings
     - String padding
     - String casing
   - String Comparision & Search
     - Caution – how NOT to compare strings
     - String comparison using like
     - String search (and replace)
4. Casting
   - Casting Methods
     - Implicit casting
     - Casting using $
       - Numerical datatypes
       - Temporal datatypes
   - Casting Textual Data
     - Strings
       - Casting to a String
       - Casting from a String
     - Symbols
       - Casting to a Symbol
       - Casting from a Symbol
5. Functions
   - Introduction to Functions
     - What are functions?
     - Function Valence
   - Defining a Function
     - Defining a function
       - Function parameters
       - Function logic
       - Returning from a function
       - Applying a function
   - Explicit & Implicit Parameters
     - Explicit parameters
     - Implicit parameters
     - Comparison
   - Function Scopt & Projections
     - Function Scope
       - Local scope
       - Global scope
     - Projections
       - Creating projections
       - Applying projections
6. Iterators
   - Introduction to to Iterators & Each
     - Introduction to iterators
     - What are iterators?
     - Mapping iterators
       - Each
   - Peach & Each-Both
     - Mapping iterators
       - Parallel each (peach)
       - each-both
   - Each-Left & Each-Right
     - Mapping iterators
       - Each-left
       - Each-right
   - Each Prior
     - Mapping iterators
       - Each prior
7. Execution Control
   - Introduction to Execution Control
     - Introduction to Execution Control
     - Signaling Errors
   - Conditional If
     - The Conditional if
   - Atomic Conditional Evaluation
     - If-else
     - Extended form of if-else
   - Vector Conditional Evaluation
     - Introduction to Vector Conditional Evaluation
   - Protected Evaluation, Do & While
     - Atomic Functions – Trap At @
     - Multivalent Functions – Trap .
     - Do
     - While
8. Scripting & Logging
   - Creating & Running a q Script
     - Introduction to Scripting & Logging
     - Creating q scripts (includes commenting)
     - Running a q script
   - Calling a Script & Parameters
     - Calling a script from another script
     - Passing parameters to a script
       - Command line parameters
       - Formatting command line parameters
   - Adding Logging to Scripts
     - Logging and how to add logs to scripts.
9. Dictionaries
   -  Introduction & Creating Dictionaries
     - Introduction to Dictionaries
     - Dictionary decomposition
     - Creating a dictionary
       - Implicit dictionary typing
       - Column dictionaries
   - Retrieval & Amendment
     - Dictionary Retrieval
       - Key lookup
       - Reverse Lookup
     - Amending dictionaries
       - Updating values
       - Removing entries
       - Subsetting entries
       - Appending to a dictionary
   - Combining Dictionaries
     - Joining two dictionaries
     - Coalesce ^
     - Mathematical Operations
10. Tables
    - Introduction to Tables
       - Table discovery
       - Table schema
    - Types of Tables
       - How to identify whether a table is keyed or unkeyed
       - Unkeyed tables
         - A table is a list of dictionaries
         - A table is a flipped column dictionary
         - A table is a collection of lists of equal length (called columns)
       - Keyed tables
         - Differences from unkeyed tables
       - Keying and unkeying a table
    - Creating Tables
       - Unkeyed Tables
         - Creating a table with existing data
         - Creating an empty table
       - Keyed Tables
    - Accessing Tables
       - Accessing columns
         - Unkeyed tables
         - Keyed tables
       - Accessing rows
       - Unkeyed tables
       - Keyed table
       - Accessing a particular cell
    - Inserting Data
       - Insert
         - Unkeyed tables
         - Keyed tables
         - Bulk inserts
       - Upsert
         - Unkeyed tables
         - Keyed tables
         - Bulk upserts  
11.  Queries -  qSQL
    - Introduction to qSQL
     - Choosing data from a table – select
       - Syntax
       - Virtual columns
       - Queries with a specified result – the select clause
     - Constraints, Aggregations & Grouping
       - Querying with aggregations
       - Queries with constraints – the where clause
       - Queries with grouping – the by clause
     - Temporal Arithmetic
      - How to use qSQL for temporal arithmetic.
     - Exec, Update & Delete
       - Extracting data from tables – exec
       - Updating/modifying table data – update
       - Remove data from table – delete
     - Fby Vs. Nested Queries
       - How to use fby to avoid nested queries in qSQL.
12.  Table Joins
     - Introduction to Joins
        - Join rows using ,
        - Join columns using ,’
     - Left Join
       - concept of keyed joins
       - left join (lj)
      - Inner Join & Asof Join
        - keyed join called the inner join (ij)
         - bitemporal joins
         - asof join.
13.  Working Files
       - Creatuing Filepaths
          - How to create filepaths with useful inbuilt functions key and hsym
        - Filepaths & sv
          - Continuing on the topic of file paths
          - Introduces sv
        - Saving & Loading kdb+ Data
          - Saving kdb+ data
          - Loading kdb+ data
        - Saving & Loading TXT Data
          - Writing to text files
          - Loading data from text data
        - Saving & Loading CSV Data
          - Saving data in CSV format
          - Loading data in CSV format
        - Saving & Loading JSON Data
          - Saving data in JSON format
          - Loading data in JSON format
14.  Inter-Process Communication
      - The first topic covers the assignment and monitoring of ports
      - The process of opening and closing connections
      - Introduces methods of executing tasks across a network handle
      - Explores both synchronous and asynchronous communication 


[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url-Bucsa]: https://www.linkedin.com/in/justin-bucsa
