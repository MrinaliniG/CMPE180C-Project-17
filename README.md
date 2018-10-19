Project Title: SUDOKU SOLUTION VALIDATOR

Project Group Number: Project 17

Team Members: 

Adithya Baskaran

Mrinalini Gopalakrishnan

Smitha Eshwarahalli Ramesh 


Abstract

Multithreading is a vital part of any software applications today. It provides a mechanism to break up a program into multiple parts and execute concurrently. This enables the utilization of the full computing benefits of multi-processor and multi-core systems. However, breaking up a job into multiple threads for parallel execution, also poses a unique set of challenges. Developers need to make vital decisions such as how to break up the tasks and data, how to address dependencies between the tasks and so on. Additionally, creating multiple threads does not automatically guarantee better performance. There are several factors which govern performance in a multithreaded application:
1. The nature of the job to be executed. All algorithms are not suitable for parallelization.
2. The percentage of task which can be run in parallel. For some applications, a significant portion of the functionality may be executed in parallel. For some others, the bulk of the functionality may involve operations like I/O which do not benefit from multithreading.
3. The number of processing cores
4. How many threads to be created for optimum performance?

In this project, we propose to implement a Sudoku Solution Validator. The purpose of Sudoku Solution Validator is to validate a given solution for Sudoku based on the game rules. We intend to implement the Sudoku Solution Validator using different threading approaches and study the effect of performance.
1. Create a separate thread to perform all column validations, a thread to perform all row validations and 9 threads to validate each of the 3*# subgrids.
2. Create 9 threads to validate each of the 9 columns, 9 threads to validate each of the 9 rows and 9 threads to validate each of the 3*3 subgrids.
3. Create a single threaded system to perform sudoku validation

