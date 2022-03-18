# Auto-Join: Benchmark data and released DLLs
Auto-Join: Joining Tables by Leveraging Program Transformations

## (1) Benchmark data:
This is the benchmark data set used in our experiments described [here](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/12/autojoin-fullversion.pdf).

### Benchmark overview
The data set has 31 test cases, each of which is a pair of Web tables, collected from [Google Tables](https://research.google.com/tables) using popular search queries that have a list intent (e.g., "list of U.S. presidents"). 

Each pair of tables have key columns that use different representations, but can nevertheless be joined using appropriate transformation. The goal is to automatically learn such transformations and produce correct join results.

### Data set description
Each folder is a test case, that contains 3 files:

* source.txt: this is one table to be joined
* target.txt: this is the other table to be joined
* ground truth.txt: this is manually determined to be the correct join results



## (2) Auto-Join DLLs:
We release the library created in the paper in AutoJoin-ReleaseDLL.zip, under a "Microsoft Research License". We hope this facilitates researchers to build on top of the library, or perform research comparisons (unfortunatel, we are not able to release source code at this time due to commercial reasons).

### Folder structure:
Code: A demo solution is in ./Code, please open AutoJoin.sln using Visual Studio (dependent DLLs are in ./Code/_DLLs).

Data: Demo data can be found in ./DemoBenchmark.

License: the DLLs are released under a "Microsoft Research License" license, please read the terms in "MSR License.docx".


### Contact:
For additional questions, please contact the authors via emails in the [paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/12/autojoin-fullversion.pdf).
