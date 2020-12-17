### [Table of Contents](https://wondwosentsige.github.io/code-301-reading-notes/Home)

## Read 14a

### Database normailization

- __Database normalization is a process used to organize a database into tables and columns.__

- The main idea with this is a table should be about a specific topic and only supporting topics included to reduce the number of duplicate data contained within your database

- There are three main reasons to normalize a database:-  
  1. The first is to minimize duplicate data. 
  2. The second is to minimize or avoid data modification issues, and 
  3. The third is to simplify queries. 


- *Normalization rules are divided into the following normal forms*: First Normal Form, Second Normal Form,Third Normal Form, BCNF, & Fourth Normal Form

- __For a table to be in the First Normal Form, it should follow the following 4 rules:__

  - It should only have single(atomic) valued attributes/columns.
  - Values stored in a column should be of the same domain
  - All the columns in a table should have unique names.
  - And the order in which data is stored, does not matter.

- For a table to be in the Second Normal Form,

  - It should be in the First Normal form.
  - And, it should not have Partial Dependency.

*- Partial Dependency occurs when a non-prime attribute is functionally dependent on part of a candidate key*

- A table is said to be in the Third Normal Form when,

  - It is in the Second Normal form.
  - And, it doesn't have Transitive Dependency.

- *A transitive dependency in a database is an indirect relationship between values in the same table that causes a functional dependency*
 
- Boyce and Codd Normal Form is a higher version of the Third Normal form. This form deals with certain type of anomaly that is not handled by 3NF. A 3NF table which does not have multiple overlapping candidate keys is said to be in BCNF. For a table to be in BCNF, following conditions must be satisfied:

  - R must be in 3rd Normal Form
  - and for each functional dependency ( X → Y ), X should be a super Key. 

- A table is said to be in the Fourth Normal Form when,

  - It is in the Boyce-Codd Normal Form.
  - And, it doesn't have Multi-Valued Dependency.





































=====================================

__Attributions for the following Reference materials and their authors__


[Database Normalization Explained in Simple English](https://www.essentialsql.com/get-ready-to-learn-sql-database-normalization-explained-in-simple-english/)


[Database normalization](https://www.studytonight.com/dbms/database-normalization.php)







[>> NEXT (Read-14b)](https://wondwosentsige.github.io/code-301-reading-notes/class-14b)