# Auto-Join
Auto-Join: Joining Tables by Leveraging Program Transformations

### Overview
This is the benchmark data set used in our experiments described [here](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/12/autojoin-fullversion.pdf).

The data set has 31 test cases, each of which is a pair of Web tables, collected from [Google Tables](https://research.google.com/tables) using popular search queries that have a list intent (e.g., "list of U.S. presidents"). 

Each pair of tables have key columns that use different representations, but can nevertheless be joined using appropriate transformation. The goal is to automatically learn such transformations and produce correct join results.

### Data set description
Each folder is a test case, that contains 3 files:

* source.txt: this is one table to be joined
* target.txt: this is the other table to be joined
* ground truth.txt: this is manually determined to be the correct join results

