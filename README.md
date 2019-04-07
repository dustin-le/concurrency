# Overview
* Simulates a professor's office hours according to his/her specific instructions.

## Functionality
* Uses threads and parallel programming to adhere to the following (changeable) restraints:
	1. Only allow 3 students in at a time.
	2. While students from class A are in his office, no students from class B are allowed to enter, vice versa. 
	3. After 10 students, the professor takes a break, and no more students are admitted into the office until the break is finished.
	4. After 5 consecutive students from a single class, the professor will answer questions from a student from the other class.
	5. If there is no student in the professor's office and he/she is not on a break, students should not wait.
* The input file details the students' information. 
	1. The first number specifies if they are class A (1) or class B (2).
	2. The second number is the time between the arrival of this student and the previous student. 
	3. The third number is the number of seconds the students need to spend with the professor.

## What I Learned
* How to effectively handle multiple threads.
* Different ways to lock and unlock threads.
* Correct mutex usage and placement.
